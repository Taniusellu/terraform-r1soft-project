
R1soft Module This module is used for creating R1soft Prerequisites Terraform 0.11.14 
Steps:
1) Edit the file below git@github.com:Taniusellu/terraform-r1soft-project.git 
2) cd infrastructure/r1soft/
3)  vi configurations/r1soft.tfvars edit backend.tf and put your bucket name 
4) terraform init 
5) source setenv.sh configurations/r1soft.rfvars 
6) terraform apply -var-file configurations/r1soft.rfvars