# Compliant Kubernetes Starter Kit for NodeJS

## How to I deploy my application?

1. Click on [Use this template](https://github.com/elastisys/ck8s-starter-nodejs/generate).
2. Change [`DOMAIN`](.github/workflows/build-and-deploy-to-ck8s.yaml) to what you got from your platform admin.
3. Create an environment `development`, and set `DOCKER_PASSWORD` and `KUBECONFIG_CONTENTS` [environment secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-an-environment) to what you got from your platform admin.
4. Done!

## How do I access my application?

Check the logs of GitHub Actions.

## Where do I find my application logs?

Check the logs of GitHub Actions.

## How do I set up alerts for my application?

Once you found you logs, check out [log-based alerts](https://elastisys.io/compliantkubernetes/user-guide/log-based-alerts/).

## I need help

Send the full output of your CI/CD pipeline to your TAM.
