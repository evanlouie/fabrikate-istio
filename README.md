# fabrikate-istio

> Currently requires the `develop` branch of Fabrikate

This component DOES NOT do automatic sidecar injection; only on namespaces labelled `istio-injection: enabled`

To enable automatic sidecar injection:

- `kubectl edit mutatingwebhookconfiguration istio-sidecar-injector`
- Remove the namespaceSelector
