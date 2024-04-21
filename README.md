# Docker Zabbix Grafana PostgreSQL NGINX 
 [Homelab]( https://akmalov.com/blog/zabbix-grafana-docker/)

## Components docker-compose:

- Postgresql 14.5
- Zabbix Server 6.2
- Zabbix Frontend NGINX 6.2
- Zabbix Agent 6.2
- Grafana 9.1.4
- ELK
- Nginx

### Easy guide

1) Clone repo:
```
git clone https://github.com/cofecofe3/zabbix-docker.git
cd zabbix-docker
```

2) Change owner grafana directory:

```
chown -R 472:472 grafana
```

3) Run docker-compose:
```
docker-compose up -d
```

### Debug
```
docker-compose logs --tail=1 -f
```
