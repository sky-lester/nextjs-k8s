# How to use helm in nextjs

## Build and push docker to the regisrty

```
docker build -t <registry>/<username>:<version> .
```

## Create helm chart
```
helm create <release> <chart>
```

## Change values in values.yaml


## Install helm chart

```
helm install <release> <chart>
```

## Change something to values.yaml
```
helm upgrade <release> <chart>
```

## List helm
```
helm list
```

## Delete or uninstall release
```
helm delete <release>
```
