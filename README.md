# Quick launch of monitoring on a single server

## Краткое описание.
Данный compose файл поднимает в docker контейнерах:
•	Prometheus (метрическая база данных) http://<host-ip>:9090
•	Grafana (визуализация метрик) http://<host-ip>:3000
•	NodeExporter (сборщик хостовых метрик);
•	cAdvisor (сборщик метрик контейнеров).


### Шаг1

Клонировать репозиторий
```
https://github.com/SterhLight/monitoring_srv.git
```
### Шаг 2

Чтобы запустить установку:
```
docker-compose up
```
