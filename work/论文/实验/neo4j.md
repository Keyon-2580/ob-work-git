``` shell
docker run -d --name neo4j -p 7474:7474 -p 7687:7687  -v /Users/keyonxie/Documents/neo4j-exp/neo4j/data:/data -v /Users/keyonxie/Documents/neo4j-exp/neo4j/logs:/logs -v /Users/keyonxie/Documents/neo4j-exp/neo4j/conf:/var/lib/neo4j/conf -v /Users/keyonxie/Documents/neo4j-exp/neo4j/import:/var/lib/neo4j/import neo4j 
```

``` shell
docker run -d --name neo4j -p 7474:7474 -p 7687:7687  -v /Users/keyonxie/Documents/neo4j-exp/neo4j/data:/data -v /Users/keyonxie/Documents/neo4j-exp/neo4j/logs:/logs -v /Users/keyonxie/Documents/neo4j-exp/neo4j/conf:/conf -v /Users/keyonxie/Documents/neo4j-exp/neo4j/import:/import -v /Users/keyonxie/Documents/neo4j-exp/neo4j/plugins:/plugins  -e NEO4J_apoc_export_file_enabled=true  -e NEO4J_apoc_import_file_enabled=true  -e NEO4J_apoc_import_file_use__neo4j__config=true -e NEO4JLABS_PLUGINS=\[\"apoc\"\] -e NEO4J_dbms_memory_heap_initial__size=6g -e NEO4J_dbms_memory_heap_max__size=6g  f55426f7a7cc
391d2ca357ed1bd343205c3a7fcc7c59e3995088066717d0d422da5986424a64
```


79密码： hyy180921wjc