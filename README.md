# Hello! Welcome to the "What do I want to eat?" app!
---
## Get Started
### These are the steps you have to take to run this app:
1. Install VirtualBox
2. Install Vagrant
3. Configure the virtual machine
    The zip file to configure the virtual machine is included. Its called 'fsnd-virtual-machine.zip'. Run this file to configure the virtual machine.
4. Power on the virtual machine
    From the command line (bash terminal), run the command `vagrant up` to do this.
5. Log into the virtual machine
    From the command line, run the command `vagrant ssh` to log in. 
6. Navigate to the folder where all the files for this project are stored.
7. Initialize the Postgres database
    From the command line, run the command `python database_setup.py`. This will set up all of the tables necessary for this app to run.
8. Start the server!
    From the command line, run the command `python main.py` to start the server.
9. Visit the website!
    The server is being hosted on port 8000. So the address is 'http://localhost:8000'

## Extra notes
There are two additional files to go with this project - the add_good_group.py and add_food_item.py files. I used these to add items to the database more easily when I first started developing this app, as I started with all CRUD functionality and had not created the website to interact with the database yet. You can run these from the command line with the command `python file_name.py`. 