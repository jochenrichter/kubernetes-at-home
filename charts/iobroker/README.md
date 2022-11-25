#iobroker

## new chart version

helm package charts/iobroker/
helm repo index --merge index.yaml --url https://jochenrichter.github.io/kubernetes-at-home/ .