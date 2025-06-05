- hosts: local
  tasks:
    - name: Ping localhost
      ansible.builtin.ping:

###
sudo ansible local -i hosts -m ping
