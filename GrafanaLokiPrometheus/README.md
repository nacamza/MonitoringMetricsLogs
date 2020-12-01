# Logs monitoring con Grafana y loki
Primero tenemos que instalar el plugin Loki a docker,
````
docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
````
Luego tenemos que reiniciar docker
````
sudo systemctl restart docker
````
Para ver los plugins instalados
````
docker plugin ls
````
[info](https://github.com/PagerTree/prometheus-grafana-alertmanager-example#installation--configuration)
