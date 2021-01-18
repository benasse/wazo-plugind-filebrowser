# wazo-plugind-filebrowser

Install [filebrowser](https://github.com/filebrowser/filebrowser) on Wazo engine

```
apt install -y wazo-plugind-cli
wazo-plugind-cli -c 'install git https://github.com/benasse/wazo-plugind-filebrowser'
```

By default the service is stopped, it has to be started with systemctl start potoo. It will run for 4 hours and then automatically stop.
