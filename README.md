![License](https://img.shields.io/badge/license-MIT-blue)
![OpenAPI](https://img.shields.io/badge/OpenAPI-3.0-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

# apispec

apispec is a developer tool for extracting API contracts from backend code,
generating OpenAPI specifications, and testing API endpoints.

It helps frontend, backend, and DevOps teams understand API structure without manually writing specs.

## Features

- Extract API routes from backend code using OpenAI
- Generate OpenAPI / Swagger spec
- View API contracts in UI
- Validate request / response schema
- Run API test requests (N/A)
- Supports Flask / FastAPI / Express style APIs

## Use cases

- API documentation
- Frontend contract generation
- API testing
- Backend validation
- CI API checks
- OpenAPI generation

## Example workflow

1. Paste backend route file
2. Generate API contract
3. View OpenAPI spec
4. Test endpoints

## Run locally

```
npm install openai dotenv fs path
cd apispec/src/
npx serve .
```

## Security

apispec does not store source code.

All processing can be done locally with local LLM URL

No training is performed on user code.

## Roadmap

- Postman style testing
- Mock server
- SDK generation
- CI integration
- CLI support

## License

MIT
