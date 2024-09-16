# Heritrix deployment and testing manual

## Deployment
```
docker compose up
```

## Testing

REST API

Get Engine Status
```
curl -v -k -u admin:admin --anyauth --location -H "Accept: application/xml" https://localhost:8443/engine
```


# References

https://github.com/ukwa/ukwa-heritrix
http://crawler.archive.org/articles/developer_manual/biblio.html#heritrix_user_manual
https://heritrix.readthedocs.io/en/latest/api.html

