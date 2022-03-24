# Linux workstation 
build Ec2 instance

this is used to create a workstation in the public subnet and will install docker kubectl helm and awscli

git clone https://github.com/thedevopsstore/prepare-workstation.git

```
cd workstation_linux
```

### Fetch the vpc tag name and subnet tag name you want your workstation to be installed

```
terraform init


terraform plan --var vpc_name= --var subnet_name= -output workstation-tf-plan

terraform apply workstation-tf-plan

ssh -i mykey ubuntu@publicip in the output
