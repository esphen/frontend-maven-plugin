# Reproducible case of mvn yarn test failing

Steps to reproduce

- Run windows with git bash shell
- `cd frontend-maven-plugin/src/it/yarn-integration/`
- `mvn package`
- It should reach the `yarn test` stage where it silently locks up forever

