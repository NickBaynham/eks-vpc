# eks-vpc

```bash
export PROJECT=$(pwd)
touch $PROJECT/terraform/{locals,main,variables,versions}.tf
```

```shell
source test.tf.vars
terraform init
terraform validate
terraform fmt
terraform plan
terraform apply
```
