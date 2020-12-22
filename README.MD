
** Login
``` 
curl --location --request POST 'localhost:1323/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "username":"odds",
    "password":"password"
}'
```

*** private route
```
curl --location --request GET 'localhost:1323/private' \
--header 'Authorization: Bearer tokenxxxx' \
```