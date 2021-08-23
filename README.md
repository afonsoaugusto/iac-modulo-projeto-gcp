# IAC Modulo Projeto GCP

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.13.0 |
| google | 3.81.0 |

## Providers

| Name | Version |
|------|---------|
| local | 2.1.0 |

## Resources

| Name | Type |
|------|------|
| [local_file.ferramenta-1](https://registry.terraform.io/providers/hashicorp/local/latest/docs/resources/file) | resource |
| [local_file.ferramenta-2](https://registry.terraform.io/providers/hashicorp/local/latest/docs/resources/file) | resource |
| [local_file.ferramenta_1](https://registry.terraform.io/providers/hashicorp/local/latest/docs/data-sources/file) | data source |
| [local_file.ferramenta_2](https://registry.terraform.io/providers/hashicorp/local/latest/docs/data-sources/file) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| ferramenta\_1 | exemplo de variavel | `string` | `"terraform"` | no |
| ferramenta\_2 | exemplo de variavel | `string` | `"ansible"` | no |
| programa | exemplo de variavel | `string` | `"mentoria-iac"` | no |

## Outputs

| Name | Description |
|------|-------------|
| ferramentas | exemplo de saidas |
<!-- END_TF_DOCS -->
## Testar localmente

Para testar o modulo localmente, você pode executar um `make test`.
