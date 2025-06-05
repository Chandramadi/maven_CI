- hosts: local
  tasks:
    - name: Ping localhost
      ansible.builtin.ping:
