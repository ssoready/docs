# SSOReady API and Fern Configuration

This repository contains your Fern Configuration:

- [OpenAPI Spec](./fern/openapi/openapi.yml)
- [Fern config](./fern/generators.yml)

## Validating your API Definition

To validate your API, run:

```sh
npm install -g fern-api # only required once
fern check
```

## Updating your SDKs

To update your SDKs, simply run the `Release Python SDK` GitHub Action with the desired version
for the release. Under the hood, this leverages the Fern CLI:

```sh
npm install -g fern-api # only required once
fern generate --group python-sdk
```
