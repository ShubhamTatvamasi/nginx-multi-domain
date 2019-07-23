# nginx-multi-domain

Start the server
```bash
docker-compose up -d
```

add the following lines in `/etc/hosts`
```
127.0.0.1 test-localhost
127.0.0.1 staging-localhost
127.0.0.1 pro-localhost
```

Test
```bash
curl test-localhost
curl staging-localhost
curl pro-localhost
```
