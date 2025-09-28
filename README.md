# Docker Workflows

Shows a job that runs in a container plus a MongoDB service container.

## What it shows

- `container:` job definition (Node image)
- `services:` for MongoDB
- Using service name as host
- Caching deps inside container job

## Flow

Run tests against a real MongoDB instance, then (in later steps) could deploy.

## Tips

- Use official images when possible
- Keep service names simple; they become hostnames
- Only add containers when you need them (don’t overuse)

## Next

See `security` for permission and safety examples.