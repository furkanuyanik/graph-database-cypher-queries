# Using GQL for Graph Database (Neo4j)
**GQL:** Graph Query Language

**Select All Data**
``` 
MATCH (n) RETURN (n) 
```

**Delete All Data**
``` 
MATCH (n) DETACH DELETE (n)
```
**Adı 'Furkan Uyanık' olan kullanıcıya gelen tüm filmleri listeleme**
```
MATCH (u:User {name: 'Furkan Uyanık'})<-[r:RATED]-(m:Movie) RETURN u,r,m
```

# to be continued
