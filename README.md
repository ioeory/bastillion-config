# bastillion-config
Config file for bastillion

## basti.service
> systemd service for bastillion, to use this service ,run bastillion initialization first
```bash
sudo tar zxvf bastillion.tar.gz -C /usr/local/
export JAVA_HOME=$JAVA_HOME
cd /usr/local/Bastillion-jetty/
sudo ./startBastillion.sh

sudo cp basti.service /lib/systemd/system/
sudo systemctl enable basti.service
sudo systemctl start basti.service
```

## nginx_reverse.conf
> nginx reverse proxy configuration for bastillion


## bastillion.xml
> bastillion jetty webapps xml configuration file
> set contextPath to the same with nginx reverse proxy configuration
