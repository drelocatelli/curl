```
curl -i -X GET http://rest-api.io/items
curl -i -X GET http://rest-api.io/items/5069b47aa892630aae059584
curl -i -X DELETE http://rest-api.io/items/5069b47aa892630aae059584
curl -i -X POST -H 'Content-Type: application/json' -d '{"name": "New item", "year": "2009"}' http://rest-api.io/items
curl -i -X PUT -H 'Content-Type: application/json' -d '{"name": "Updated item", "year": "2010"}' http://rest-api.io/items/5069b47aa892630aae059584
```

# Token Authorization
```
curl -H "Authorization: OAuth <ACCESS_TOKEN>" http://www.example.com
curl -H "Authorization: Basic <_your_token_>" http://www.example.com
curl -H "Authorization: Bearer xxxxxxxxxxxxxx" https://www.example.com/
```
