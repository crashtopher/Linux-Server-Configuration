To Run This Program:
1. open Terminal and cd to ~/fullstack/vagrant/authorization to ensure you are in the correct directory
2. run command vagrant up to power on the virtual machine
3. run command vagrant ssh to be promted with the vagrant command shell
4. import the database:
    - run cd /vagrant
    - run python database_setup.py
    - if you want to prepopulate the database run python lotsofmenus.py
5. start the server by running python project.py
6. navagate to the webapp by putting "localhost:5000" in your web browser!
7. Have fun!