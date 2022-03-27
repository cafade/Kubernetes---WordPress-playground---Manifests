## Kubernetes - WordPress playground - Manifests 
Taken from: https://www.civo.com/learn/moving-wordpress-to-civo-kubernetes. Some manifests were outdated, like 
the ones from cert-manager, and Traefik ingress. 

The Civo cluster didn't allow the installation of Longhorn like suggested in the example, its containers wouldn't start,
the events said that the minimum amount of nodes for it to work are 3, no matter the amount of nodes used (cluster had 6).