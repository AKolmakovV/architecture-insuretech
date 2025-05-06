
# Задание 5. Проектирование GraphQL API

Swagger контракт: ./Task5/swagger.yaml

GraphQL контракт: ./Task5/schema.graphql

### Пример использования:

```

 query {
   client(id: "123") {
     id
     name
     age
     documents {
       id
       type
       number
     }
     relatives {
       id
       relationType
       name
     }
   }
 }

```
