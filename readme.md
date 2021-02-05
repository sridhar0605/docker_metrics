# Source 
https://github.com/vegasbrianc/prometheus
https://hub.docker.com/r/infinityworks/docker-hub-exporter/
https://github.com/vegasbrianc/docker-pulls/blob/master/docker-compose.yml
https://github.com/vegasbrianc/docker-pulls/blob/master/prometheus.yml


# misc
tweak the input params in the stack yaml to query for either the 
all the repos under an user name or particular repo's

mod these lines
```
  - "IMAGES=sridnona/crispresso, sridnona/mutation_caller, sridnona/rnaseq_docker"
       # - "ORGS=sridnona"
```

![](metrics.gif)
