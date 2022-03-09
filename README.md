# helm-charts
Helm charts repository

## instructions

1. Bump chart version in Chart.yaml
2. Build package:

```bash
helm package dir/sub-dir # To where your Chart.yal can be found
```

3. Build new index.yaml file:

```bash
helm repo index .
```

4. Please note it can take a few minutes for GH Pages to reflect the updated index.
