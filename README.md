# APIs in Azure API Mangement

## Steps

-   Use extension to generate OpenAPI YAML definition
-   Complete API YAML
    -   Servers: localhost:7071
    -   New path: HelloWorld
    -   Query string parameter
    -   Text/plain response
-   Preview it using extension
-   Create Azure Function
-   Add the CORS rule
-   Run it
-   Use the try it in the extension
-   Create GitHub Action workflow

## Todo

-   Don't keep adding CORS (and really all the other settings) to the Function App - i.e.
    don't keep recreating it.
