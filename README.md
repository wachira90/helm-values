# helm-values
helm values example


helm create meet

## windows

helm template web .\meet -f .\values.yml

helm template web .\meet -f .\values.yml > meet.yml


## linux

helm template web ./meet -f ./values.yml

helm template web ./meet -f ./values.yml > meet.yml
