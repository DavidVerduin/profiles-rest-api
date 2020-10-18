# Profiles REST API

Profiles REST API course code.

To initialize the development environment, do as follows:

In the command line, type:
# To start the virtual machine, whose /vagrant directory will be syncronized with your development directory
vagrant up

# To connect, via ssh, to the virtual machine located in your computer
vagrant ssh

# To exit the virtual machine, when you are finished
exit

# To create the python environment 
python -m venv ~/env

# To activate, and enter, the python local environment
source ~/env/bin/activate

# To exit the environment
deactivate

# To install, inside the python local enviroment, all the dependencies
pip install -r requirements.txt

# To run the django development server

python manage.py runserver 0.0.0.0:8000