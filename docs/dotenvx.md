# Managing dotenvx-encrypted secrets

We use [`dotenvx`](https://dotenvx.com) CLI to easily manage project level and org-wide secrets without having to mingle between secrets management dashboards and Doppler service account tokens.

## Centralized secret store repo

The Alumni Society utilizes [Recap Time Squad](https://recaptime.dev)'s [centralized dotenvx-based secret store setup](https://github.com/recaptime-dev/dotenvx-secretstore), under the [`alumni-society/main` branch of its own fork](https://github.com/hackclub-alumni/dotenvx-secretstore/tree/alumni-society/main/projects/hackclub-alumni), for Git-based SecretOps.

[The included documentation](https://github.com/recaptime-dev/dotenvx-secretstore/tree/main/docs) has details from setting up to using them within the CI and more.

## Safekeeping `.env.keys`

It's important to safely store the `.env.keys` somewhere, especially loss of these private keys result in loss of access to those secrets, hence triggering data loss and unwarranted API key rotation.

You may opt to use 1Password and other password managers with CLI tooling but always check the docs if it requires storing another set of credentials in GitHub Actions secrets or can be authenticated via OIDC.
