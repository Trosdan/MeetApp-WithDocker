# MeetApp With Docker

```
git clone https://github.com/Trosdan/MeetApp-WithDocker.git
```

Abrir arquivo docker-compose.yml e trocar `localhost` por seu endereço IP local

```
environment:
  - DB_HOST=192.168.0.108
  - REDIS_HOST=192.168.0.108
```

Por fim rodar.

```
docker-compose up
```

Codigo fonte dos projetos

- [MeetApp FronEnd](https://github.com/trosdan/meetapp-frontend)
- [MeetApp BackEnd](https://github.com/trosdan/meetapp-backend)
