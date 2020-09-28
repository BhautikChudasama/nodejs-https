# nodejs-https

## Install ```Let's Encrypt library```

```bash
sudo apt-get install letsencrypt
```

## Run the command
```bash
sudo certbot certonly --standalone
```

Make sure you run all commands with ```sudo``` becuase certificates are stored in ./etc/... and PORT 80 can only run by ```ROOT``` user.


