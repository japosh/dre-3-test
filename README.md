# dre-test

### Service startup

#### Run `docker-compose up`: 
![alt text][docker-compose-up]

#### Check services are running with `docker ps` (or `docker-compose ps`): 
![alt text][docker-ps]

#### Check Airflow healthcheck with `http://localhost:8080/health` (Also used on container healthcheck): 
![alt text][airflow-healthcheck]

### Usage

#### Access Airflow UI with `http://localhost:8080`: 
![alt text][airflow-ui]

#### Smooth operator DAG run succeeds and logs the following: 
![alt text][dag-run-log]

### Test resolution

#### Procedures taken in this test can be checked [here](docs/resolution-notes).

### Extras

#### Simple architecture diagrams can be found [here](docs/airflow-architecture.drawio).

[docker-compose-up]: https://github.com/japosh/dre-3-test/raw/main/docs/images/docker-compose-up.png "docker-compose up execution"
[docker-ps]: https://github.com/japosh/dre-3-test/raw/main/docs/images/docker-ps.png "docker ps"
[airflow-ui]: https://github.com/japosh/dre-3-test/raw/main/docs/images/airflow-ui.png "Airflow webUI"
[airflow-healthcheck]: https://github.com/japosh/dre-3-test/raw/main/docs/images/airflow-healthcheck.png "Airflow healthcheck"
[dag-run-log]: https://github.com/japosh/dre-3-test/raw/main/docs/images/dag-run-log.png "Airflow success DAG run log"
