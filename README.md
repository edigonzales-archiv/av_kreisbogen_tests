# av_kreisbogen_tests

Datenbank:
```
vagrant up
```

DB-Schemas anlegen (mit und ohne Kreisbogen):

```
java -jar ~/apps/ili2pg-3.12.2/ili2pg-3.12.2.jar --dbhost 192.168.50.8 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --nameByTopic --defaultSrsCode 2056 --sqlEnableNull --createBasketCol --createDatasetCol --models DM01AVCH24LV95D --dbschema av_arcs --schemaimport

```
```
java -jar ~/apps/ili2pg-3.12.2/ili2pg-3.12.2.jar --dbhost 192.168.50.8 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --nameByTopic --defaultSrsCode 2056 --sqlEnableNull --strokeArcs --createBasketCol --createDatasetCol --models DM01AVCH24LV95D --dbschema av_strokes --schemaimport
```





