# Nginx PHP MySQL

Docker managing and monitoring tools running Portainer, InfluxDB, cAdvisor and Grafana

**THIS ENVIRONMENT SHOULD ONLY BE USED FOR DEVELOPMENT!**

**DO NOT USE IT IN PRODUCTION!**

## Images to use

* [Portainer](https://hub.docker.com/r/portainer/portainer/)
* [InfluxDB](https://hub.docker.com/r/tutum/influxdb/)
* [cAdvisor](https://hub.docker.com/r/google/cadvisor/)
* [Grafana](https://hub.docker.com/r/grafana/grafana/)
* [Busybox](https://hub.docker.com/_/busybox/)

## Start using it

1. Download it :

    ```sh
    $ git clone https://github.com/alfredopenaalonso/docker_tools.git
    ```

2. Run :

    ```sh
    $ docker-compose up -d
    ```

## Directory tree

```sh
├── data
│   └── grafana
│   └── influxdb
│   └── portainer
├── .gitignore
├── docker-compose.yml
├── LICENSE.md
└── README.md
```
