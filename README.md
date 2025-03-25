# argocd-example-deployments

This repository holds an [example ApplicationSet](./appset.yaml) to show how to use an ArgoCD ApplicationSet with git generator.

There are also 3 different application deployment definition:
`deploy.yaml` files define to deploy which app with which version and release name etc,
`config.yaml` files hold config values for each app.

Directory structure:

```sh
.
├── appset.yaml
├── dev
│   ├── cert-manager
│   │   ├── config.yaml
│   │   └── deploy.yaml
│   ├── ingress-nginx
│   │   ├── config.yaml
│   │   └── deploy.yaml
│   └── nginx
│       ├── config.yaml
│       └── deploy.yaml
├── stage/
└── prod/
```
