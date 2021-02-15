# ansible_tower_cisco


#--Cent OS download
http://mirrors.piconets.webwerks.in/centos-mirror/8.3.2011/isos/x86_64/

#--install ansible in centos
https://linuxhint.com/install_ansible_centos8/

#--Ansible Tower in Centos
https://computingforgeeks.com/install-and-configure-ansible-tower-on-centos-rhel/

#--License
https://docs.ansible.com/ansible-tower/latest/html/userguide/import_license.html?extIdCarryOver=true&sc_cid=701f2000001OH7EAAW


# AWX - Ubuntu
https://computingforgeeks.com/how-to-install-ansible-awx-on-ubuntu-linux/
# AWX - Centos
https://computingforgeeks.com/install-and-configure-ansible-awx-on-centos/
------
Error handling
In case of the following error:

"/bin/sh: docker-compose: command not found"
You will have to add the Docker-compose executable manually, execute the following:

sudo curl -L "https://github.com/docker/compose/releases/download/1.28.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

# Install VS Code in Centos 8

$ sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc

$ sudo vi /etc/yum.repos.d/vscode.repo

          *** Insert following VS Code repostory to the file***
[code]
name=Visual Studio Code
baseurl=https://packages.microsoft.com/yumrepos/vscode
enabled=1
gpgcheck=1
gpgkey=https://packages.microsoft.com/keys/microsoft.asc

$sudo dnf install code

$ code or open application under activity and then VS Code
