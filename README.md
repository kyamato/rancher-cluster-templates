# rancher-cluster-templates (Working)

⚠️ This project is still in active development. As we continued to develop it, there will be breaking changes. ⚠️

This project contains the Helm Chart for Rancher Cluster Templates, which provide declaritive manifests to deploy clusters with the [Rancher Multi-Cluster Manager](https://github.com/rancher/rancher). Please start with the Helm Chart [README](/charts/cluster-templates/README.md)!

## Configuration

### Adding the Helm Chart via CLI

```bash
helm repo add cluster-templates https://rancherfederal.github.io/rancher-cluster-templates
helm repo update
```

### Adding the Helm Chart via OCI

```bash
ghcr.io/rancherfederal/charts/rancher-cluster-templates
```

### Adding the Helm Chart via Rancher Manager

1. Authenticate into the Rancher Manager UI
2. Open the local cluster or downstream cluster
3. Click into Apps -> Charts -> Repositories
4. Click "Create" and enter the following information:

```bash
Name: cluster-templates
Target: http(s) URL to index generated by Helm
Index URL: https://rancherfederal.github.io/rancher-cluster-templates
Authentication: None
```
