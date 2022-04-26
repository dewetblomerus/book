# Use Docker Compose to run LiveBook on my Raspberry Pi

### Run some setup code inside the container

```
# Get inside the container
docker exec -it livebook-dewet bash
# Run the required mix commands
mix local.hex
mix local.rebar --force
```
