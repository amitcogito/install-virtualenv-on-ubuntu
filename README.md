### How to install virtualenv on ubuntu:

### Install **pip** first

    sudo apt-get install python3-pip

### Then install **virtualenv** using pip3

    sudo pip3 install virtualenv 

### Now create a virtual environment 

    virtualenv envOne 

### you can use any name insted of **envOne**

### You can also use a Python interpreter of your choice

    virtualenv -p /usr/bin/python2.7 envOne
  
### Active your virtual environment:    
    
    source envOne/bin/activate
    
### Using fish shell:    
    
    source envOne/bin/activate.fish

### To deactivate:

    deactivate

### Create virtualenv using Python3
    virtualenv -p python3 envTwo

### Instead of using virtualenv you can use this command in Python3
    python3 -m venv envTwo
