# HelmCharts
This Helm Charts Repository contains packaged Helm Chart to install unification-service app provided by Lalit Arora
This Chart was produced to install unification-service using Helm Charts 3


# Add Repository 
`$ helm repo add osl-helm-repo https://gemalto.helmrepo.io/HelmCharts/osl`   
`$ helm repo update`

## Install Packages (unification-service)  
`$ helm install unification-service unification-service-repo/unification-service [--version=1.0.0]`

