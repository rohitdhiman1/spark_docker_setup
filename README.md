# spark_docker_setup
Repo to kickstart Apache Spark on Docker

1. Start docker compose `docker compose up -d`
2. Start interactive shell `docker exec -it /bin/bash`

Note - Line #15 in docker compose file indicates the mounting path
In this case, the directory that contains docker compose file will be accessible under path `/test-files` in the docker container interactive shell. The mounting path can be adjusted as per convenience.