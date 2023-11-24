
  # Without Multi-Stage Build:
  App successfully deployed  with a standard Dockerfile, but docker image size is big at 867MB. The Docker image includes all the build tools, dependencies, and artifacts in a single layer. This often results in a larger image size, as the image carries unnecessary files and tools used during the build process, which are not required for the runtime environment. It works, but wondering if there's a way to make it more efficient. 
