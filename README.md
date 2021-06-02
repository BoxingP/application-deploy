# Build an Application

## Steps

1. Install Ansible

1. Install collections from Ansible Galaxy

   ```
   $ ansible-galaxy collection install -r requirements.yaml
   ```

1. Run playbook:

   ```
   $ ansible-playbook playbook.yaml
   ```

Then the [EPO portal](https://github.com/thermofisher/dscops-epo-portal) will be deployed in Linux.