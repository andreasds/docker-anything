# MySQL Docker

Example to initialize MySQL Docker

## Installation

### Start service

```bash
make start
```

### Stop service

```bash
make stop
```

## Configuration

- `MYSQL_VERSION`: MySQL Docker version
- `MYSQL_DATABASE`: Database
- `MYSQL_DATA_HOST`: Host path to store MySQL data at host
- `MYSQL_HOST_PORT`: MySQL published host port
- `MYSQL_PASSWORD`: Database access password
- `MYSQL_ROOT_PASSWORD`: Database root access password
- `MYSQL_USER`: Database username

## Reference

- [MySQL] Docker Official Images

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

  [MySQL]: https://hub.docker.com/_/mysql
