# Sanneh-cyberLab
we are implementable the secalable infracstructure to support our CIA commitment.
we provissioned several resure in Azure cloud to support these goals.
# Resources
   1. Load Balancer thet blances traffic between our 2 web servers
   2. 2 web Servers "Web 1 and Web 2
   3. Jump Bpx that we SSH into to access all the resources in  the cloud from the Headquaters 
   4. ELK-Server we have the Elk server to monitor traffic and performance on web 1 and 2. 
# Whats in Each Machine
    Web 1 with an ip addres of 10.0.0.5 and Web 2 with Ip addres of 10.0.0.6 both runs the DVWA the configuration file is located in the Ansible folder "pentest.yml" file
    The jump Box with the Private IP of 10.0.0.4 and public ip of 168.61.50.174 have Docker container installed in it which runs our Ansible files. 
    The Elk- server runs the Kibana where it gets its configuration file from the Docker container. these configuration files are located in "Filebeat.yml and Metricbear.yml" these configuration files are located in the Ansible folder
    
   
