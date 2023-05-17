# terraform-password
Terraform module to generate string passwords


<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0.0 |
| <a name="requirement_random"></a> [random](#requirement\_random) | >= 3.0.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_random"></a> [random](#provider\_random) | >= 3.0.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [random_password.this](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/password) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_length"></a> [length](#input\_length) | (Number) The length of the string desired. The minimum value for length is 1 and, length must also be >= (min\_upper + min\_lower + min\_numeric + min\_special). | `number` | n/a | yes |
| <a name="input_override_special"></a> [override\_special](#input\_override\_special) | n/a | `string` | `""` | no |
| <a name="input_special"></a> [special](#input\_special) | n/a | `bool` | `true` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_bcrypt_hash"></a> [bcrypt\_hash](#output\_bcrypt\_hash) | n/a |
| <a name="output_id"></a> [id](#output\_id) | n/a |
| <a name="output_result"></a> [result](#output\_result) | n/a |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
