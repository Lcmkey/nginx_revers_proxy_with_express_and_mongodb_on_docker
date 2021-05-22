# nginx_revers_proxy_with_express_and_mongodb_on_docker

### Start the Application

```bash
$ docker-compose up -d
```

### Destroy the Application

```bash
$ docker-compose down --rmi all --remove-orphans
```

> Once the application has started, the mongo directory will save previouly data, you need to delete all files first. otherwise, the mongodb container will fail to start