# MYANSIBLE22
--- 
- hosts: all 
  become: yes 
  tasks: 
  - name: install git 
    apt: 
    state: present 
  - name: install wget
    apt: 
      name: wget 
      state: present 
  - name: install tree 
    apt: 
      name: tree
      state: present 
      