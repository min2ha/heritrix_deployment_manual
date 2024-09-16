# Heritrix deployment and testing manual

##Deployment
docker compose up


##Testing
REST API

Get Engine Status
```curl -v -k -u admin:admin --anyauth --location -H "Accept: application/xml" https://localhost:8443/engine
```


References

https://heritrix.readthedocs.io/en/latest/api.html
