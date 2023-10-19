### Ansible Playbook for automating deployment of my web scraper server (WIP)
I find myself reconfiguring server anew whenever I need just one app to work for couple days, so I decided to automate the process with one playbook to not repeat myself anymore.
### Prerequisites 
- Ubuntu sever
- Ansible on terminal and host
### Run with
```console
ansible-playbook run.yml -K -e "username=<username> password=<password> host_name=<host_name or ip_address> ssh_private_key_path=<ssh_private_key_path>"
```
