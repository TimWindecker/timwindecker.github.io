# Use official Bun image
FROM docker.io/oven/bun:latest

# System settings
USER root

# Create workspace
RUN mkdir -p /workspace
WORKDIR /workspace

#######################
# System Dependencies #
#######################

# Install dependencies
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y \
    git \
    curl \
    # Clean up apt caches to keep the image size down
    && rm -rf /var/lib/apt/lists/*

#################
# Astro Project #
#################

# Astro dev server port
EXPOSE 4321

# Disable Astro's telemetry
RUN bun astro telemetry disable

CMD ["bun", "run", "dev", "--host", "0.0.0.0"]
