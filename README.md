# Blog API using FastAPI and uvicorn

#### Here we are building APIs easily and fast(according to docs) using FastAPI.
#### But first we need to install fastapi and uvicorn : pip install fastapi uvicorn

#### FastAPI is not concerned with the function names but with the routes.
#### It also provides automatic api documentation using swagger-ui and redoc.
#### We can also change the routes of api docs in the initialization of FastAPI instance.

#### In the routes we can also provide path params which FastAPI recoganises if they are in curly braces, otherwise if we only give params in the function arguments they are treated as query params.

#### When you need to send data from a client (let's say, a browser) to your API, you send it as a request body.