# Production Ready Charts

The charts in this repo use operational best practices for running
"applications" on production Kubernetes clusters.

# Repositories

| Name | Description |
| --- | --- |
| [shared](shared/) | Not intended to be used directly but as building blocks |
| [production](production/) | Contains the actual charts |


## FAQ

### What is a "Production Ready Chart"?

A chart that takes into consideration the following:

1. Running an application in a highly available, fault tolerant way
1. Considers security as an essential feature
1. Configures monitoring and alerting solution(s)