# Main community helm chart storage

* helm create mychart
* helm package mychart
* mv mychart-0.1.0.tgz $YOUR_PATH/activiti-cloud-helm-charts
* cd $YOUR_PATH/activiti-cloud-helm-charts
* helm repo index . --url https://activiti.github.io/activiti-cloud-helm-charts/
* git add -i
* git commit -av
* git push origin master
