# Deployment

- `deploy.yml` is the main deploy script.
- `environments` contains configurations for all the possible environments we deploy to
- `inventory` mainly contains secrets to be interpolated into the `application.properties` file in the `environments` subdirectory for the environment we're deploying to
