# network-firmware-update
Updating firmware on network devices with Ansible and AAP

PoC on updating firmware on a Cisco Switch

![Update automation process](update_process.png)

# Prereq

On Tower system
```
source /var/lib/awx/venv/ansible/bin/activate
umask 0022
pip install scp
chown awx:awx -R /var/lib/awx/venv/ansible/bin/activate
```
