# What is it 
This is a set of ansible scripts that can fetch `.cfg` files from Windows servers

This is tested on Ubuntu 2024.04 on WSL2

# How to run 

- Install ansible (sudo apt install ansible)
- Update the inventory file with username,password and ips

- Use the following command to 
 ```
 ansible-playbook -i inventory.ini copy_cfg_to_local.yaml
 ```

