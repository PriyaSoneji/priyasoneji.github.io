# Use the official Ruby image as a base
FROM ruby:3.2

# Install dependencies
RUN apt-get update && \
    apt-get install -y build-essential nodejs && \
    gem install bundler jekyll

# Set the working directory
WORKDIR /workspace

# Expose the default Jekyll port
EXPOSE 4000

# Default command (can be overridden by devcontainer.json)
CMD ["bash"]
