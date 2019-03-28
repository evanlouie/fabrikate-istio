# fabrikate-istio

> Requires at least [0.1.4](https://github.com/Microsoft/fabrikate/releases) or later of [Fabrikate](https://github.com/Microsoft/fabrikate).

## Common Configs

Custom chart changes:

| Setting                         | Value          | Description                                        |
| ------------------------------- | -------------- | -------------------------------------------------- |
| global.proxy.includeIPRanges    | "0.0.0.0"      | Allows all egress traffic by default               |
