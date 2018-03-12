# GraphQLBundleDemo

## Install

```
composer install
bin/console c:w
```

## Start server

```
bin/console server:run
```

## Important files

### quickstart

* [Schema](config/graphql/types/query.graphql)
* [ResolverMap](src/Resolver/MyResolverMap.php)

## Endpoints

### quickstart

* [GraphQL](http://127.0.0.1:8000/graphql/quickstart)
* [GraphiQL](http://127.0.0.1:8000/graphiql/quickstart)

## Example

```graphql
{
  humans {
    name
    id
    status
    direwolf {
      name
    }
    dateOfBirth
  }
}
```
