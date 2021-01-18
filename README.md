# wazo-plugind-filebrowser

Install [filebrowser](https://github.com/filebrowser/filebrowser) on Wazo engine

```
apt install -y wazo-plugind-cli
wazo-plugind-cli -c 'install git https://github.com/benasse/wazo-plugind-filebrowser'
```

By default the service is stopped, it has to be started with `systemctl start filebrowser`.

Now you can browse your file system via your web browser on port 8003 without password.

The service will run for 4 hours and then automatically stop.
