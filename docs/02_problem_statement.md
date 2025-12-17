# Problem Statement

In many development environments, applications work only on the developer’s local machine due to differences in dependencies, runtime environments, or configurations.

Manual Docker image creation and pushing can lead to:
- Inconsistent builds
- Human error
- Lack of auditability
- Security risks from exposed credentials

The goal of this project is to solve these problems by implementing a fully automated CI pipeline that:
- Builds Docker images consistently
- Validates Dockerfiles using best practices
- Pushes images securely to a container registry
- Eliminates manual intervention
