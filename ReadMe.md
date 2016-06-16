# Ansible Demo Overview #

- Go over Vagrant files and VirtualBox
- Show the BitBucket web site
- Git clone example web page from Bitbucket to workstation
- Build Ansible server with Vagrant
- Display ad-hoc Ansible commands
- Build demo server with Vagrant
- Go over the playbook details (located in /ansible on the vagrant VM)
- Run the playbook
  - Configure some basic options: ntp, snmp, resolv.conf
  - Setup web server
  - Git clone the web files from Bitbucket
- Show web page running on the newly built server
- Edit web content on the workstation and commit wit Git
- Push to Bitbucket and show versioning
- Re-run the playbook to show Git pulling the newly changed files
- Show the updated web page on the web server

## Git Commands ##

>  git --version  
>  git clone https://git_host/user_name/web_demo.git .  
>  git add .  
>  git commit -m "Add initial commit"  
>  git push -u origin master  


## Vagrant Commands ##
>  vagrant --version  
>  vagrant up  
>  vagrant ssh  
>  vagrant destroy  
>  vagrant box add <box_name>  
>  vagrant box update  


## Ansible Commands ##
>  ansible --version  
>  ansible all -m ping -u root -k  
>  ansible all -m setup -u root -k  
>  ansible-playbook site.yml  


## Links ##
Git - https://git-scm.com/  
BitBucket - https://bitbucket.org/  
Vagrant - https://www.vagrantup.com/  
Atlas (Vagrant Boxes) - https://atlas.hashicorp.com/boxes/search  
VirtualBox - https://www.virtualbox.org/wiki/Downloads  
Atom - https://atom.io/  
Ansible Docs - http://docs.ansible.com/  
