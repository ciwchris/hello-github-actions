# APIs in Azure API Mangement

## Steps

- Use extension to generate OpenAPI YAML definition
- Complete API YAML
  - Servers: localhost:7071
  - New path: HelloWorld
  - Query string parameter
  - Text/plain response
- Preview it using extension
- Create Azure Function
- Run it
- Use the try it in the extension
- Create GitHub Action workflow for Func
- Commit and let workflow complete
- Use the try it for the deployed Func (remember CORS)
- Workflow for APIM
- Commit and let workflow complete
- Use the test tool to exceed the limit

## Todo

-   Don't keep adding CORS (and really all the other settings) to the Function App - i.e.
    don't keep recreating it.
- Create API using OpenAPI spec and mock result
- Create a logic App and add it to API
