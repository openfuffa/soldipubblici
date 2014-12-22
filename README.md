## #soldipubblici

Some cool stuff about #soldipubblici soldipubblici.gov.it

### Tutti gli enti e i codici
```
curl -X GET http://soldipubblici.gov.it/it/chi/search/%20  \                         ⏎
-H "Accept: application/json, text/javascript, */*; q=0.01" \
-H "X-Requested-With: XMLHttpRequest" > codici_ente.json
```

### Tutti i dati per un certo ente
```
curl -i -X POST http://soldipubblici.gov.it/it/ricerca \
-H "Content-Type: application/x-www-form-urlencoded; charset=UTF-8" \
-H "Accept: Application/json" \
-H "X-Requested-With: XMLHttpRequest" --data "codicecomparto=REG&codiceente=000705604"
```
