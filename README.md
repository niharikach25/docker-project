# docker-project

With Multistage Build:

With multistage builds, you organize your Dockerfile into multiple stages, each with a specific purpose.

Advantages:

Reduced Image Size: The final image only includes the essential components needed to run the application, omitting unnecessary build artifacts and tools.
Improved Security: By separating the build and runtime environments, you minimize the attack surface of the final image
