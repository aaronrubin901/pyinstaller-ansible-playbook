# pyinstaller-ansible-playbook
ansible-playbook as executable  

# Prerequisite 
    - python3
    - pip 

# Install dependencies 

```pip3 install pyinstaller six ansible```

# Build ansible-playbook executable 

```pyinstaller ansible.spec --onefile```


# Use the executable - copy to /usr/local/bin/ on instance without python3
```scp dist/ansible-playbook ubuntu@1.2.3.4:/usr/local/bin/ansible-playbook```