# bastillion-config
Config file for bastillion

## basti.service
> systemd service for bastillion, to use this service ,run bastillion initialization first
```bash
sudo cp basti.service /lib/systemd/system/
sudo systemctl enable basti.service
sudo systemctl start basti.service
```

## nginx_reverse.conf
> nginx reverse proxy configuration for bastillion


## bastillion.xml
> bastillion jetty webapps xml configuration file
> set contextPath to the same with nginx reverse proxy configuration
