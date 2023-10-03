# HelmCharts
This Helm Charts Repository contains packaged Helm Chart to install student-producer app provided by Lalit Arora
This Chart was produced to practice Helm Charts 3


# Add Repository 
`$ helm repo add student-producer-repo https://aroralalit.github.io/HelmCharts/student-producer`   
`$ helm repo update`

## Install Packages (student-producer)  
`$ helm install student-producer-release student-producer-repo/student-producer [--version=1.1.0]`

