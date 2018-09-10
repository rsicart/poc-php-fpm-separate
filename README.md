# Poc nginx fpm k8s using different pods

## Important notice

Splitting nginx and fpm using different deployments in a public cloud using
multiple zones can add network latencies between nginx and fpm.


## Components

nginx
* deployment
* service
* ingress (exposed publicly)

fpm
* deployment
* service


