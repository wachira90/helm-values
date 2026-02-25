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
