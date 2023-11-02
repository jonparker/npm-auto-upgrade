# A Github Workflow for testing with different node versions

This repo demonstrates setting up a workflow with a dynamic version of Node as well as defaulting to the version in the `.nvmrc` for PRs.

Run the action manually to use a specific version of Node

Action: https://github.com/jonparker/npm-auto-upgrade/actions/workflows/testing.yml

<img width="398" alt="image" src="https://github.com/jonparker/npm-auto-upgrade/assets/152131/77dd8b2c-fba3-438b-8e6a-73f24ec6d8e8">

Otherwise when triggered by a PR it will run with the version in the `.nvmrc` file.
