# ldoc-anible
Ansible repo for "Linux for Devops and Cloud" course

# Users and Permissions — SIS2

How to run:

1. Review `ansible/inventory.ini`, replace `ansible_host` with your server(s).
2. Put your automation public key into `ansible/files/automation_bot_ed25519.pub`.
3. Run: `ansible-playbook -i ansible/inventory.ini ansible/site-users.yml --ask-become-pass`.
4. Check screenshots in `screenshots/` for expected evidence to include in the report.
