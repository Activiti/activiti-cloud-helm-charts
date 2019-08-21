# activiti-cloud-helm-charts

helm create mychart
helm package mychart
mv mychart-0.1.0.tgz docs
helm repo index docs --url https://activiti.github.io/activiti-cloud-helm-charts/
git add -i
git commit -av
git push origin master
