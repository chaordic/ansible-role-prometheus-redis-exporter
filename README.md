# Ansible Role: prometheus-redis-exporter

Ansible role to install and configure prometheus redis exporter

## Role Variables
```yaml
redis_exporter_version: v0.11.3

redis_exporter_log_path: /var/log/redis-exporter.log

redis_exporter_addrs: "localhost:6379,localhost:6380"
redis_exporter_aliases: "redis_instance1,redis_instance2"
```
## License

GPLv3

## Author Information

Cloud Infrastructure Team, Linx Impulse
