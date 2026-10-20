# Minimal Helm Chart Skeleton (Lite)

## English

A Deployment-only Helm 3 chart: `Chart.yaml`, `values.yaml`, and one template. The default image is `registry.example.com/sample-web:1.0.0`, an example path. A second values file points at `registry.example.com/shop/bulletin:2.0.1`. The full chart adds the Service, the Ingress, the label helpers, and the summary script.

### Deliverables

- `deliverables/sample-web/Chart.yaml` — chart metadata, apiVersion v2
- `deliverables/sample-web/values.yaml` — replica, image, port, probe, resources
- `deliverables/sample-web/templates/deployment.yaml` — Deployment template
- `deliverables/sample-web/templates/NOTES.txt` — short render note
- `examples/shop-image-values.yaml` — filled bulletin image and replica count
- `examples/README.md` — what those values set
- `LICENSE` — MIT

## 中文

只含 Deployment 的 Helm 3 chart：`Chart.yaml`、`values.yaml` 和一个模板。默认镜像是示例路径 `registry.example.com/sample-web:1.0.0`。另一份 values 指向 `registry.example.com/shop/bulletin:2.0.1`。完整版另有 Service、Ingress、标签辅助模板和摘要脚本。

### 交付文件

- `deliverables/sample-web/Chart.yaml`
- `deliverables/sample-web/values.yaml`
- `deliverables/sample-web/templates/deployment.yaml`
- `deliverables/sample-web/templates/NOTES.txt`
- `examples/shop-image-values.yaml`
- `examples/README.md`
- `LICENSE`

Full version: GUMROAD_URL
