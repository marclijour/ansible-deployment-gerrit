# Deploy Gerrit on Ubuntu with Ansible
Check run.sh for the command to run in the Bash shell.

## Prerequisites
1) You must have provisioned a server. Take note of its IP address.

2) You must have installed Python on the server (remote host).
~~~~
$ sudo apt update 
$ sudo apt install python
~~~~

3) You must have installed Ansible on your local machine.
~~~~
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
~~~~

## Modus Operandi (M.O.)
Edit inventory to change the IP with your server IP.
Run the command you see in run.sh.

Alternatively, make run.sh executable and run it.

