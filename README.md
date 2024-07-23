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

For others:
- `Service` focuses on `selector` and `ports`.
- `Deployment` emphasizes on `replicas`, `selector`, and `template`.
- `Job` 


Start from `Service`
```yaml
spec:
  selector:
    <key>: <value>
  ports:
    - protocol: <protocol>
      port: <service-port>
      targetPort: <container-port>
  type: <service-type>
  
```

Start from `Deployment`
