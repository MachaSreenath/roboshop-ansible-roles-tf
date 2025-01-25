### while working with this roles, we given variable name in main.yaml and we have to pass the variable value at the execution time, like:

" ansible-playbook -i inventory.ini -e ansible_user=centos -e ansible_password=DevOps321 -e component=mongodb main.yaml "

--> If any extra files like mongodb.repo, catalogue.servie... are there we have to put in files folder inside mongodb, so when the playbook starts execution and it sees mongodb.repo file so it goes to the files folder and checks it is there or not. 

--> "common" is also like a role where we can keep repeated things(code) between all the roles and call it whenever required. 