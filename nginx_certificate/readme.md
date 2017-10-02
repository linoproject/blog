# Test connection with curl
```
openssl pkcs12 -export -inkey client.key -in client.crt -name test-curl-client-side -out client.p12

curl -k --cert client.p12:<passwd> https://test.local/test.html
```
