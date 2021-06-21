# ecr-exporter

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.1.0](https://img.shields.io/badge/AppVersion-0.1.0-informational?style=flat-square)

A Helm chart for the AWS ECR Prometheus exporter

**Homepage:** <https://github.com/aws-exporters/charts/tree/main/charts/ecr-exporter>

## Installation
```
helm repo add aws-exporters https://aws-exporters.github.io/charts/
helm install ecr-exporter aws-exporters/ecr-exporter
```

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| js-timbirkett |  |  |

## Source Code

* <https://github.com/aws-exporters/ecr>
* <https://aws.amazon.com/ecr/>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| env | list | `[]` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"ghcr.io/aws-exporters/prometheus-ecr-exporter"` |  |
| image.tag | string | `""` |  |
| imagePullSecrets | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podAnnotations | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| securityContext | object | `{}` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| tolerations | list | `[]` |  |