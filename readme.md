# Source 
[prometheus](https://github.com/vegasbrianc/prometheus)
[docker-hub-exporter](https://hub.docker.com/r/infinityworks/docker-hub-exporter/)
[docker-compose](https://github.com/vegasbrianc/docker-pulls/blob/master/docker-compose.yml)
[prometheus yaml](https://github.com/vegasbrianc/docker-pulls/blob/master/prometheus.yml)


# misc
tweak the input params in the stack yaml to query for either the 
all the repos under an user name or particular repo's

mod these lines in the yml  stack
```
  - "IMAGES=sridnona/crispresso, sridnona/mutation_caller, sridnona/rnaseq_docker"
       # - "ORGS=sridnona"
```

![](metrics.gif)

# TO-DO
- Create a json plugin that can be loaded in to [grafana-dashboard](https://grafana.com/grafana/dashboards)
- If you have a plugin handy spin up local instance of grafana `GF_SERVER_ROOT_URL=http://localhost:8181` 
- Feel free to edit params in config.monitoring file
