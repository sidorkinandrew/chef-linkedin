# chef-linkedin

curl -L https://omnitruck.chef.io/install.sh | sudo bash

curl https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk -c stable

Node bootstrapping:

knife bootstrap FQDN/IP -U USERNAME -i /PATH/TO/IDENTITY_FILE --sudo -N web1 -r "recipe[apache]"

