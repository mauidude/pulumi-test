# Pulumi Test

Proof of concept getting pulumi to work with localstack on Docker (Compose).

## Requirements

- docker-compose
- `PULUMI_ACCESS_KEY` set on host

## To Run

```bash
# start localstack (s3)
$ docker-compose up -d localstack

# create aws resources  on localstack using pulumi
$ docker-compose up pulumi
```
