# API Spec & Mock Builder

Inspects backend controllers, route files, and database schemas to generate valid OpenAPI 3.1 specifications, TypeScript client typings, and realistic mock fixtures.

## Working Folder Structure

- Backend Routes: `./routes/`
- Schemas & Models: `./schemas/`
- Output OpenAPI Specs: `./specs/`
- TypeScript Typings: `./types/`
- Mock Payloads: `./mocks/`

## Example Prompts

- "Generate an OpenAPI 3.1 specification from the route handlers in ./routes/."
- "Extract TypeScript interface types from the schemas in ./schemas/models.ts."
- "Generate mock response JSON fixtures for our user and payment endpoints."
