# ansible-playbooks

Ansible Playbook for Rack application stack that installs PostgreSQL, Nginx, Passenger, and Ruby on rbenv.

    $ ansible-playbook -i hosts nginx-passenger-setup.yml

Sample Sinatra application:

    http://sample.192.168.33.11.xip.io/

Or, to use Unicorn instead of Passenger.

    $ ansible-playbook -i hosts nginx-setup.yml

