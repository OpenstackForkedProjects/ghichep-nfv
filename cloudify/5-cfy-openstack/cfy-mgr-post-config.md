### Post configuration on cloudify manager
```sh
sudo yum group install -y "Development Tools"
sudo yum install -y python-devel.x86_64
sudo echo "<ops_ctl_ip> controller" >> /etc/hosts
```
