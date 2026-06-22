# Service Mesh Config 🕸️

Istio service mesh with mTLS, traffic management, and observability.

## Features

- **mTLS**: Automatic mutual TLS
- **Traffic Management**: Canary, A/B, circuit breaking
- **Observability**: Distributed tracing, metrics
- **Security**: Authorization policies

## Install

```bash
istioctl install --set profile=default
kubectl apply -f manifests/
```

## License

Apache 2.0