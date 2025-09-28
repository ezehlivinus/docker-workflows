# Docker Workflows

Container job plus MongoDB service.

## Purpose
Run tests against a real database inside CI.

## Highlights
- Job-level `container` image
- MongoDB service container
- Hostname = service name
- Dependency cache inside container

## Flow
Start DB service → run app/tests in container.

## Notes
Add containers only when they give needed parity.

## Next
`security`