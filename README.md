<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
</p>

# GraphQL Singapore

Welcome! We're really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Refactored Pet Library](http://funded-pet-library.moonhighway.com/)
- [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [SWAPI: Star Wars API](http://graphql.org/swapi-graphql/)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### GraphQL Schema Definition Language

- [Schema Definition Language Slides](https://slides.com/moonhighway/schema-definition-language/)
- [City to City Through Types](https://codesandbox.io/s/5vzn2rkzxn)
- [Modular Schema](https://github.com/eveporcello/schema-workshop/tree/master/06-extras/modularizing-a-schema/finished)
- [Lab Instructions](https://slides.com/moonhighway/schema-lab/)
- [Lab Repository](https://github.com/graphqlworkshop/schema-activity)
- [Mocking](https://github.com/graphqlworkshop/mocking)

### Building a GraphQL API

- [Exercise Start Files](https://github.com/graphqlworkshop/snowtooth-api)
- [Simple Strava Sample](https://github.com/eveporcello/simple-strava-sample/blob/master/index.js)
- [REST Data Sources](https://github.com/MoonHighway/countries-datasources)
- [Resolvers - PayPal Blog](https://medium.com/paypal-engineering/graphql-resolvers-best-practices-cd36fdbcef55)

### Unions and Interfaces

- [Unions & Interfaces Slides](https://slides.com/moonhighway/unions-interfaces)
- [Union Types](https://codesandbox.io/s/rm2rx3opqm)
- [Interfaces](https://codesandbox.io/s/71x8n304r1)

### Client Intro Samples

- Simple cURL Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### Auth Examples

- [Pet Library](https://pet-library.moonhighway.com)
- [Pet Library Implementation](https://github.com/MoonHighway/pet-library/blob/initial-version/src/resolvers/Mutation.js)

## Next Steps

- [Fullstack Error Handling with GraphQL](https://blog.apollographql.com/full-stack-error-handling-with-graphql-apollo-5c12da407210)
- [Apollo Federation](https://egghead.io/playlists/getting-started-with-apollo-federation-60ad0165)

## Evaluation
* [Mid Class Evaluation](https://docs.google.com/forms/d/e/1FAIpQLSdXC0vnTSlw65WzTnmqYml-QK9v_3qR9kVozQ0AEkCNtUFRMg/viewform?usp=sf_link) -- http://bit.ly/graphql-singapore
