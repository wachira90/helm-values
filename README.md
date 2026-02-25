# helm values example

## create

```sh
helm create meet
```

## windows

```bat
helm template web .\meet -f .\values.yml

helm template web .\meet -f .\values.yml > meet.yml

helm template web .\meet -f .\values.yml --set image.tag="dev1.0.0"
```

## linux

```sh
helm template web ./meet -f ./values.yml

helm template web ./meet -f ./values.yml > meet.yml

helm template web ./meet -f ./values.yml --set image.tag="dev1.0.0"
```

## test 

```sh
helm template meet meet -f values.yml --set image.tag="1.29.5-alpine3.23-slim"

helm template -n test meet meet -f values.yml

helm install -n test meet meet -f values.yml

helm uninstall -n test meet

helm list -n test

helm ls -n test
```