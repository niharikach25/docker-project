Without Multistage Build:
In a traditional Docker build without multistage, you typically have a single Dockerfile with multiple commands to set up the environment, install dependencies, build the application, and then run it. The resulting image includes both the build tools and artifacts, leading to a larger image size.

Issues:

Image Size: The final image may include unnecessary files, libraries, and tools that were only needed during the build process, making it larger than necessary.
Security: Including build tools in the final image might expose security risks, as these tools are not required for the application to run.
