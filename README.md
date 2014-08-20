# ansible-playbooks

## rails-setup.yml

Ansible Playbook for Rack application stack that installs PostgreSQL, Nginx, Passenger, and Ruby on rbenv.

    $ ansible-playbook -i hosts rails-setup.yml

Sample Sinatra application:

    http://sample.192.168.33.11.xip.io/
