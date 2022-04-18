![MerokuDAO](./img/logoBIG.jpeg)

Meroku-DAO is the world's first community-owned omni-chain dApp store. We strive to eliminate the redundant costs which exist in web2 (eg. cloud hosting ) and centralised authorities who control access and define their own rules eventually hindering dApp developers from innovating. We feel the future will be self-hosted dApp stores with complete transparency. This framework is the start of that journey, please join us and let's together head towards an inclusive, fair and secured web3 for all.

Please note: We don't have a website or any token. This repo is the only official spot.

## Benefits:

- It allows you (the user) to install and run dApps locally. Complete trust and security + self hosting. 
- It allows you (the developer of dApp) to distribute it to a huge audience without hosting
anywhere.


# Prerequisites

Docker Desktop is required. [Install Docker Desktop](https://www.docker.com/products/docker-desktop/)

# Usage (for users)

## Add an app

`node -r ts-node/register src/app.ts add <repoUrl> <name>`

Adds a public git repo hosted at `repoUrl` with the name `name` to local hosting.

## Start an app

`node -r ts-node/register src/app.ts start <name>`

## Stop an app

`node -r ts-node/register src/app.ts start <name>`


## Repos with which this can be tried

- https://github.com/r4881t/v4-ui
- https://github.com/r4881t/cryptoboys-nft-marketplace


# For Developers

In order to make your repo compatible with Meroku, you will need to add a file called `Selfhosting` and specify an appropriate environment file. The details of both are given below.

1. [`Selfhosting` file Spec](docs/Selfhosting.md)
2. [Environment Variables](docs/EnvironmentVariables.md)

# Contributing

Community Guidelines Coming Soon.

# Roadmap

Check out the [roadmap](docs/Roadmap.md).
