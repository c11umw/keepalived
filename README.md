# keepalived
Sample Scripts for **keepalived** - used to create a VIP making our PiHoles High Available

Visual Install and method inspired from: https://youtu.be/q-QIrzFeIxw?t=423


**keepelived.conf** files on both Primary and Secondary are saved to `/etc/keepalived/keepalived.conf`


```sh
sudo apt update
sudo apt-install keepealived -y

sudo systemctl enable --now keepalived.service
sudo systemctl status keepalived.service
```
