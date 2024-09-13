## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.61.0 |
| <a name="requirement_yandex"></a> [yandex](#requirement\_yandex) | 0.129.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_yandex"></a> [yandex](#provider\_yandex) | 0.129.0 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_instance_1"></a> [instance\_1](#module\_instance\_1) | ./modules/instance | n/a |
| <a name="module_instance_2"></a> [instance\_2](#module\_instance\_2) | ./modules/instance | n/a |

## Resources

| Name | Type |
|------|------|
| [yandex_iam_service_account.sa](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/iam_service_account) | resource |
| [yandex_iam_service_account_static_access_key.sa-static-key](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/iam_service_account_static_access_key) | resource |
| [yandex_lb_network_load_balancer.ynlb](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/lb_network_load_balancer) | resource |
| [yandex_lb_target_group.ynlb_group](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/lb_target_group) | resource |
| [yandex_resourcemanager_folder_iam_member.sa-editor](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/resourcemanager_folder_iam_member) | resource |
| [yandex_storage_bucket.skillboxtestbucket999](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/storage_bucket) | resource |
| [yandex_vpc_network.network](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/vpc_network) | resource |
| [yandex_vpc_subnet.subnet1](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/vpc_subnet) | resource |
| [yandex_vpc_subnet.subnet2](https://registry.terraform.io/providers/yandex-cloud/yandex/0.129.0/docs/resources/vpc_subnet) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_cloud_id"></a> [cloud\_id](#input\_cloud\_id) | Default cloud | `string` | `"b1gdidpooa0ines7f08m"` | no |
| <a name="input_folder_id"></a> [folder\_id](#input\_folder\_id) | Default folder ID in yandex cloud | `string` | `"b1grophk8r8v2edae95c"` | no |
| <a name="input_token_id"></a> [token\_id](#input\_token\_id) | Default token | `string` | `"y0_AgAAAAABtdKkAATuwQAAAAEQsUSqAADUCiZ4uWlF6LwzxJamX1Drd4Ju3w"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_external_ip_address_vm_1"></a> [external\_ip\_address\_vm\_1](#output\_external\_ip\_address\_vm\_1) | n/a |
| <a name="output_external_ip_address_vm_2"></a> [external\_ip\_address\_vm\_2](#output\_external\_ip\_address\_vm\_2) | n/a |
| <a name="output_internal_ip_address_vm_1"></a> [internal\_ip\_address\_vm\_1](#output\_internal\_ip\_address\_vm\_1) | n/a |
| <a name="output_internal_ip_address_vm_2"></a> [internal\_ip\_address\_vm\_2](#output\_internal\_ip\_address\_vm\_2) | n/a |
