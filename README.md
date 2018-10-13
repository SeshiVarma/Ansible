# Ansible
--- 
  - hosts: all
    tasks:
      - name: creating the empty file
        file:
          path: /tmp/raju
          state: touch
