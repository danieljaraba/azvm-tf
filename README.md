# azvm-tf

Daniel Jaraba

---

## How to run:

### Requeriments:

- SO with Terraform installed and logged in an Azure account.
- ```.tfvars``` file with the values for the variables defined in ```variables.tf```.

### Steps:

1. Prepare working directory for Terraform:

```
terraform init
```

2. Validate terraform configuration:

```
terraform validate
```

3. Validate and show the changes required for this configuration:

```
terraform plan
```

4. Create the infrastructure:

```
terraform apply
```

---

## About:

IaC for Azure Virtual Machine defined in Terraform with a public IP that permits connect via SSH.

### Main:

Contain the resources required for the virtual machine:

- Azure Resource Group.
- Azure Virtual Network.
- Azure Subnet.
- Azure Public IP.
- Azure Network Interface.
- Azure Network Security Group.
- Azure Network Interface Security Group Association.
- Azure Network Security Rule.
- Azure Virtual Machine.
  * Storage OS Disk.
