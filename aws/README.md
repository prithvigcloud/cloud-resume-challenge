## Using Cloudformation templates

we have multiple options for IaC:
- CloudFormation
- CDK
- Terraform

we are going to use cloudFormation because it is dead simple to use.
 
## Installing Ansible

``` sh
pipx install --include-deps ansible

ansible-galaxy collection install amazon.aws

```

## Edit Vault 

We are goind to store all of our configuration in a vault.
We dont have to, but just for learnng well use a vault even for non -sesitive information

```sh

cd aws
ansible-vault create playbooks/vaults/prod.yml
ansible-vault edit playbooks/vaults/prod.yml
``` 

## Edit Vault



