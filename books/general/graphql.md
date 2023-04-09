# Notes on "Craft GraphQL APIS in Elixir with Absinthe.."

## Key Takeaways:

## Chapter Summaries

### Part 1 = Build a GraphQL API

#### 1. Meet GraphQL

Building APIs that support a wide range of possible clients can be challenging.
GraphQL is a query language that lets API users describe the data they want,
while API creators can focus on data relationships and business rules. GraphQL
allows for more flexibility in API endpoints compared to REST. Understanding the
structure of GraphQL query documents is important in working with GraphQL.
Comparing GraphQL to REST can help developers understand the benefits of using
GraphQL.

##### GraphQL Simplifies Things

- GraphQL can significantly shorten development time by allowing clients to
  query exactly the data they need.
- With GraphQL, clients can query across data relationships, getting all the
  desired information in a single request.
- GraphQL provides a declarative query language that tells clients the shape of
  the expected response, reducing guesswork and the need for documentation
  spelunking.
- Backend developers can gain a detailed picture of the data that clients need,
  allowing them to avoid sending unnecessary data across the wire.
- GraphQL is similar to SQL in that it allows users to retrieve exactly what
  they need, but it is simpler to use and customize.
