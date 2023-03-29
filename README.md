# Deploy the catalog source
```
oc apply -f config/samples/catalogsource.yaml
```

# Query on the status of catalog source 
```
oc get catalogsources -n openshift-marketplace
```

# Validating the application
``oc expose svc/visitors-frontend-service -n openshift-operators # select the route and you will be redirected to the application
```