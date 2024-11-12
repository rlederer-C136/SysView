Running with Profiles:

On Linux (Ubuntu/WSL2): Use the linux profile to enable network_mode: host and GPU support:

$ docker-compose --profile linux up

On macOS or Windows: The services will use the default profile and map the necessary ports:

$ docker-compose up

This approach allows a single Docker Compose file that works across Linux, macOS, and Windows, adapting to 
the platform's specific needs via profiles and network configuration.
