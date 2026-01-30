# Action Repo

This repository is used to trigger GitHub Webhook events (Push, Pull Request, Merge) for the TechStax assessment.

## Purpose

Actions performed in this repository (pushes, PRs, merges) send webhooks to the `webhook-repo` application, which visualizes these events.

## Usage

1.  Add the Webhook URL from your running `webhook-repo` instance (e.g., via ngrok) to this repository's settings.
2.  Perform actions:
    - **Push**: `git push`
    - **Pull Request**: Open a PR.
    - **Merge**: Merge a PR

    change