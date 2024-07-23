# renocrypt-k8s-starter

## Kubernetes Resource Types Summary

### Common Structure
> **ALL** resources shares `apiVersion`, `kind`, `metadata` 

```yaml
apiVersion: <version>
kind: <resource-type>
metadata:
  name: <resource-name>
spec:
  # source specific fields
```

Start from `Service`
```yaml
spec:
  
```

Start from `Deployment`
