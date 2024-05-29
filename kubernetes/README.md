# Kubernetes integracija

Komande za kluster:
```
helm upgrade --namespace="pgo" --create-namespace --atomic --install pgo oci://registry.developers.crunchydata.com/crunchydata/pgo
```

Chart za mongo db
```
helm upgrade --namespace="banka-3-dev" --create-namespace --atomic --install mongodb oci://registry-1.docker.io/bitnamicharts/mongodb
```