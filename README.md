# hasura local setup

## Setup

```bash
# run containers
docker-compose up -d
```

## Endpoints

Use VSCode REST Client extension to test the endpoints in `rest.http` file.

On clean metadata, all the endpoints returns response like this:

```json
HTTP/1.1 404 Not Found
// headers of response be here

{
  "code": "not-found",
  "error": "Endpoint not found",
  "path": "$"
}
```
