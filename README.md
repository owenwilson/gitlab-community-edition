# Gitlab-ce docker-compose Example

## Description

- This docker-compose file is just an example of deploying gitlab community

## Download image gitlab-ce

```sh
docker pull gitlab/gitlab-ce:latest
```
## Create Folders

```sh
mkdir -p /mnt/mygitlab/config
mkdir -p /mnt/mygitlab/logs
mkdir -p /mnt/mygitlab/data
```
## Deploy

```sh
docker-compose -f docker-compose.gitlab-ce.yml
```

## Contributions

- [owenwilson](https://github.com/owenwilson)

## Donations

- [voluntary donations! devfrustrado](https://www.paypal.com/paypalme/devfrustrado)
