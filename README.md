# Ansible-Final-Task

```bash
Using Terraform, I managed to biuld a complete infrastructure of a VPC, Nat & Internet Gateway, 1 public load balancer, 1 public instance & two private instances to deploy Nexus & SonarQube.
```
# Note: to be able to ssh to a private instance using ansible you should create a config file and put in it the following:

```bash
Host bastion
        hostname bastion_public_ip
        user ubuntu
        port 22
        identityfile /path/to/bastion/key.pem
```
