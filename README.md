Here I have created ansible playbooks to create ec2 instances of different OS distributions and also to stop ec2 instances depending upon their OS family

I have used the concepts like loops, idempotency to write the playbooks

The keys are kept secret by using "ANSIBLE-VAULT" concept

In the ec2_create.yaml file, I have written the playbook for creating ec2 instances

In the ec2-stop.yaml file, I have written the playbook for stopping the ec2 instances and I have also used "DEBUG" for gathering facts (like: os.family)

In the inventory.ini file, I have listed the created instances information and clubbed them into "ALL" (ex: ec2-user@ip)
