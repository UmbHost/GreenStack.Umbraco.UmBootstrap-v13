# GreenStack.Umbraco.UmBootstrap-v13

A GitHub template repository for Umbraco 13 (LTS) with the [UmBootstrap](https://marketplace.umbraco.com/package/umbraco.community.templates.umbootstrap) starter kit, preconfigured for [GreenStack](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting) hosting.

## What's included

- Umbraco 13 (LTS) on .NET 8
- UmBootstrap starter kit
- Forwarded headers middleware for Traefik proxy
- HTTPS runtime validator removed (SSL terminated by GreenStack)
- Data protection keys persisted to `/app/keys` in production
- Multi-stage Dockerfile exposing port 8080
- Docker launch profile (HTTP)
- Dependabot configured for weekly Umbraco updates

## Getting started

1. Click **"Use this template"** on GitHub to create a new repository
2. Clone your new repository
3. Follow the [Getting Started with Umbraco 13 on GreenStack](https://umbhost.net/gb/blog/2026/03/getting-started-with-umbraco-13-on-greenstack-with-github) guide

Alternatively, install via dotnet new:

```bash
dotnet new install UmbHost.GreenStack.Umbraco.UmBootstrap::13.*
dotnet new greenstack-umbraco-umbootstrap -n MyProject
```

## GreenStack

- [Purchase GreenStack hosting](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting)
- [GreenStack documentation](https://my.umbhost.net/knowledgebase/17/GreenStack)
- [GreenStack CI/CD samples](https://github.com/UmbHost/GreenStack.CICD.Samples)

## License

MIT
