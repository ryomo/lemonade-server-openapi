# Lemonade Server OpenAPI

## Overview

This is an OpenAPI spec for the Lemonade Server API, converted from the official [Lemonade Server Spec](https://lemonade-server.ai/docs/server/server_spec/).

It is designed to be used with Swagger UI, allowing you to easily explore and test the API endpoints.

## Usage

```sh
docker compose up -d
```

Then, open `http://localhost:8080` in your browser to access Swagger UI.

## Limitations

- Audio responses are not playable in Swagger UI.
  - See [Audio returned by POST request is not playable. · Issue #8378 · swagger-api/swagger-ui](https://github.com/swagger-api/swagger-ui/issues/8378)
- `/realtime` endpoint is omitted since it uses WebSocket, which is not supported by OpenAPI and Swagger UI.
