# Bulletin values

Filled values for the lite Deployment template.

- Release name is whatever you pass to Helm. The template names the Deployment `<release>-web`.
- Image: `registry.example.com/shop/bulletin:2.0.1` (example registry path, not a published image)
- Replicas: 1
- Container port: 8080, probe path `/healthz`
- CPU request: `20m`

The full chart adds a Service, an Ingress, and shared label helpers. Check upstream docs for the image you run.
