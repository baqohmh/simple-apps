# Create env variable

```
vim .env
```

```
DB_NAME=training
DB_HOST=ipaddress
DB_USER=peserta
DB_PASS=password
APP_PORT=3000
```

sonar-scanner-npm \
  -Dsonar.host.url=http://172.23.13.85:9000 \
  -Dsonar.token=sqp_46ed5601fe9a5ae7bfd878121a663e288dd0c649 \
  -Dsonar.projectKey=simple-apps