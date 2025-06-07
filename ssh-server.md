# Create SSH Server on your local machine

### Install openssh-server
    sudo apt-get install openssh-server

### Check the status openssh-server
    sudo systemctl status ssh
- this always listens to port 22


### Allow file transfer openssh-server
    sudo ufw allow ssh

### Get the ip
    ip a

### To connect the ssh server
    ssh -p <port_number> <username>@<ip_address>


## If Inactive then


### To start the ssh server
    sudo systemctl start ssh


### To active the ssh server
    sudo systemctl active ssh
