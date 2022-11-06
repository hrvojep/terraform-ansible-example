# terraform-ansible-example

Simple example of provisoning a VM on AWS and invoking Ansible to configure Nginx website

### to run
terraform init

terraform plan

terraform apply


ansible-playbook -u ubuntu --key-file ansible-key.pem -T 300 -i 'x.x.x.x,', app.yml

