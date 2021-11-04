# Ansible F5 Automation IMmersion Day Workshop
You will use Ansible commands and playbooks to explore and reconfigure a F5 in a virtual environment.  Note, that even though we are using a virtual environment, this is not a requirement, everything we do, can be done on physical devices.   

The Immersion Day is meant as a follow on to the Network Automation Immersion Day.  Some content will be review but in respect to using Ansible with F5.  While you can go through these labs there may be concepts that were covered previously that we will not cover as it is expected that these concepts are already understood.  Throughout the labs we hope to share some additional features, elements, good and bad practices and patterns to using Ansible for Automation. 

You will be required to modify some files during the course of this workshop.  You will not be required to write your own playbooks as this would require much more time.  The playbooks used are open source and thus free to use and modify.  That being said, writing playbooks and running them in a test environment is one of the best ways to learn.   
## Outline
* Part 1: Getting setup
    * Fork Git Repo
    * SSH to jump station 
    * Connecting to F5 
    * Downloading forked Git Repo 
* Part 2: Basic F5 labs 
Explore the lab environment 
Modify files in Git Repo 
Gather data from F5 
Adding nodes to F5 
Adding a load balancing pool 
Adding members to a pool 
Adding a virtual server 
Adding and attaching an iRule to a virtual server 
Save the running configuration 
Part 3: F5 operational labs 
Disabling a pool member 
Deleting F5 configuration 
Error Handling 
Part 4: F5 AS3 labs 
Intro to AS3 
Operational change with AS3 
Deleting a web application 
Part 5: Tower labs 
Explore Ansible Tower 
Create an Ansible Tower job template 
Create an Ansible Tower workflow 
Create a node maintenance workflow 
