# loggerhead
## API Documentation (SwaggerIO)

### Downloading the Editor
Checkout the Docker instructions on the [SwaggerEditor repo](https://github.com/swagger-api/swagger-editor).

You can use the editor to load up the `api.yaml` file here in the code and edit the api definition. 

### Viewing the Documentation
You can build a SwaggerUI that will run on port 81 of your localhost using docker:
```bash
docker pull swaggerapi/swagger-ui
docker run -p 81:8080 swaggerapi/swagger-ui
```
Then you can navigate to `localhost:81` and enter `https://raw.githubusercontent.com/erebuseternal/loggerhead/main/api.yaml` into the search bar.
