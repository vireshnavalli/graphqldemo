This is hands-on project done to showcase capabilities of GraphQL over REST API.
1. Flexibility in Data Retrieval: GraphQL Allows clients to request exactly the data they need in a single query. This reduces over-fetching and under-fetching of data.
2. Single Endpoint : Uses a single endpoint for all requests. The structure of the request defines what data is needed.
3. Efficient Data Loading : Can optimize data retrieval by batching and caching requests. Clients can fetch nested resources in a single request
4. Strongly Typed Schema : Defines a strongly-typed schema using a type system. This ensures that clients know exactly what data is available and the types of that data.
5. Tooling and Ecosystem : Offers a rich ecosystem of tools for schema validation, query testing, and API documentation (e.g., GraphiQL, Apollo).
6. Versioning: Avoids the need for versioning by allowing clients to request the exact fields they need. Changes to the schema can be additive and backward-compatible.
7. Real-time Data: Supports real-time data updates with subscriptions. This is useful for applications that need to reflect live data changes (e.g., chat applications, live sports scores).
8. Developer Experience: Improves developer experience by providing clear and precise API interactions. The self-documenting nature of GraphQL schemas and tools like GraphQL enable easier debugging and faster development.

Use Cases
GraphQL: Ideal for applications with complex data requirements, real-time updates, and where performance optimization is critical. Suitable for front-end applications needing flexibility and efficiency in data fetching.
________________________________________________
Run the above project as : mvn spring-boot:run
Sample output: <img width="924" alt="image" src="https://github.com/vireshnavalli/graphqldemo/assets/26489144/64bdc698-c9e9-4a76-9108-04adbc0867b7">

