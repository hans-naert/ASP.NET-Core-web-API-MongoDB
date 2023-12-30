## create JWTS token
```
dotnet user-jwts create --issuer dotnet-user-jwts
```

## do CURL request with generated token
```
curl -i -H "Authorization: Bearer {token}" https://localhost:7019/api/books
```