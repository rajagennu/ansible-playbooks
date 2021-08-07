using docker to spin containers, so I am using them for VMs
- installation: there is docker install playbook available
- networking: I am using static IP, instructions are at https://thelinuxmen.blogspot.com/2021/08/docker-networking-basisc-configure.html
- commands

    ``````bash
    ```bash
    docker pull ubuntu:latest
    docker container run --net mydockernetwork --ip 172.18.0.4 -it --name webserver ubuntu
    docker container run --net mydockernetwork --ip 172.18.0.5 -it --name dbserver ubuntu
    ```
- todo : May be a docker compose for above configuration is a good idea.
