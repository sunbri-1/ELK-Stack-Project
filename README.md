## Automated ELK Stack Deployment

The files in this repository were used to configure the network depicted below.

![TODO: Update the path with the name of your diagram](Images/diagram_filename.png)

These files have been tested and used to generate a live ELK deployment on Azure. They can be used to either recreate the entire deployment pictured above. Alternatively, select portions of the _____ file may be used to install only certain pieces of it, such as Filebeat.

  - _TODO: Enter the playbook file._

This document contains the following details:
- Description of the Topologu
- Access Policies
- ELK Configuration
  - Beats in Use
  - Machines Being Monitored
- How to Use the Ansible Build


### Description of the Topology

The main purpose of this network is to expose a load-balanced and monitored instance of DVWA, the D*mn Vulnerable Web Application.

Load balancing ensures that the application will be highly _____, in addition to restricting _____ to the network.
- _TODO: What aspect of security do load balancers protect? What is the advantage of a jump box?_

Integrating an ELK server allows users to easily monitor the vulnerable VMs for changes to the _____ and system _____.
- _TODO: What does Filebeat watch for?_
- _TODO: What does Metricbeat record?_

The configuration details of each machine may be found below.
_Note: Use the [Markdown Table Generator](http://www.tablesgenerator.com/markdown_tables) to add/remove values from the table_.

| Name     | Function | IP Address | Operating System |
|----------|----------|------------|------------------|
| Jump Box | Gateway  | 10.0.0.1   | Linux            |
| TODO     |          |            |                  |
| TODO     |          |            |                  |
| TODO     |          |            |                  |

### Access Policies

The machines on the internal network are not exposed to the public Internet.

Only the _____ machine can accept connections from the Internet. Access to this machine is only allowed from the following IP addresses:
- _TODO: Add whitelisted IP addresses_

Machines within the network can only be accessed by _____.
- _TODO: Which machine did you allow to access your ELK VM? What was its IP address?_

A summary of the access policies in place can be found in the table below.

| Name     | Publicly Accessible | Allowed IP Addresses |
|----------|---------------------|----------------------|
| Jump Box | Yes/No              | 10.0.0.1 10.0.0.2    |
|          |                     |                      |
|          |                     |                      |

### Elk Configuration

Ansible was used to automate configuration of the ELK machine. No configuration was performed manually, which is advantageous because...
- _TODO: What is the main advantage of automating configuration with Ansible?_

The playbook implements the following tasks:
- _TODO: In 3-5 bullets, explain the steps of the ELK installation play. E.g., install Docker; download image; etc._
- ...
- ...

The following screenshot displays the result of running `docker ps` after successfully configuring the ELK instance.

![TODO: Update the path with the name of your screenshot of docker ps output](Images/docker_ps_output.png)

### Target Machines & Beats
This ELK server is configured to monitor the following machines:
- _TODO: List the IP addresses of the machines you are monitoring_

We have installed the following Beats on these machines:
- _TODO: Specify which Beats you successfully installed_

These Beats allow us to collect the following information from each machine:
- _TODO: In 1-2 sentences, explain what kind of data each beat collects, and provide 1 example of what you expect to see. E.g., `Winlogbeat` collects Windows logs, which we use to track user logon events, etc._

### Using the Playbook
In order to use the playbook, you will need to have an Ansible control node already configured. Assuming you have such a control node provisioned:

SSH into the control node and follow the steps below:
- Copy the _____ file to _____.
- Update the _____ file to include...
- Run the playbook, and navigate to ____ to check that the installation worked as expected.

_TODO: Answer the following questions to fill in the blanks:_
- _Which file is the playbook? Where do you copy it?_
- _Which file do you update to make Ansible run the playbook on a specific machine? How do I specify which machine to install the ELK server on versus which to install Filebeat on?_
- _Which URL do you navigate to in order to check that the ELK server is running?

_As a **Bonus**, provide the specific commands the user will need to run to download the playbook, update the files, etc._
Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/README
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ ls
 __MACOSX/                                  'Brian '                                   Career/                   'Fax cover to MDH for CEUs.doc'   myoutput.tx        myoutput.txtt   'Python Scripts'/
 13-Elk-Stack-Project_Resources_README/     'Brian Sundberg S Resume 04 23 2015.doc'  'Cyber Aces'/               Finance/                         myoutput.txt       mytestplayfile   README/
 13-Elk-Stack-Project_Resources_README.zip  'Brian To Do List 08 05 20.docx'          'Cybersecurity Bootcamp'/   GitHub/                          myoutput.txt.doc  'Play Files'/    'The Linux Command Line.pdf'

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ cd 13-Elk-Stack-Project_Resources_README

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README
$ ls
__MACOSX/  README/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README
$ cd README/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ ls
Images/  README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ nano README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ ls
 __MACOSX/                                  'Brian '                                   Career/                   'Fax cover to MDH for CEUs.doc'   myoutput.tx        myoutput.txtt   'Python Scripts'/
 13-Elk-Stack-Project_Resources_README/     'Brian Sundberg S Resume 04 23 2015.doc'  'Cyber Aces'/               Finance/                         myoutput.txt       mytestplayfile   README/
 13-Elk-Stack-Project_Resources_README.zip  'Brian To Do List 08 05 20.docx'          'Cybersecurity Bootcamp'/   GitHub/                          myoutput.txt.doc  'Play Files'/    'The Linux Command Line.pdf'

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop
$ ls
'Amazon Music.lnk'*   desktop.ini           'Google Drive.lnk'*  'Katie (50).jpg'        lesson1.py             'Millennium Trust account sign up.pdf'   Slack.lnk*       'Visual Studio Code.lnk'*
 Brian/              'GitHub Desktop.lnk'*   Grammarly.lnk*      'leah birth cert.pdf'  'Microsoft Teams.lnk'*   popeyelikesspinach                      Vagrantfile.txt   Zoom.lnk*

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop
$ cd Brian/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ cd GitHub/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub
$ ls
ELK-Stack-Project/  uofm-stp-cyber-pt-09-2020-u-c/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub
$ cd ELK-Stack-Project/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project (main)
$ ls
Ansible/  Diagrams/  Images/  Linux/  README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project (main)
$ cd Diagrams/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams (main)
$ ls
ELK_Project_Diagram.drawio

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams (main)
$ cp ELK_Project_Diagram.drawio >> ELK_Project_Diagram.png
cp: missing destination file operand after 'ELK_Project_Diagram.drawio'
Try 'cp --help' for more information.

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams (main)
$ cp ELK_Project_Diagram.drawio >> ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams/ELK_Project_Diagram.png
cp: missing destination file operand after 'ELK_Project_Diagram.drawio'
Try 'cp --help' for more information.

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams (main)
$ pwd
/c/Users/Brian & Katie/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project/Diagrams (main)
$ cd ../../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub
$ cd ELK-Stack-Project/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project (main)
$ ls
Ansible/  Diagrams/  Images/  Linux/  README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub/ELK-Stack-Project (main)
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/GitHub
$ cd ../

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ ls
 __MACOSX/                                  'Brian '                                   Career/                   'Fax cover to MDH for CEUs.doc'   myoutput.tx        myoutput.txtt   'Python Scripts'/
 13-Elk-Stack-Project_Resources_README/     'Brian Sundberg S Resume 04 23 2015.doc'  'Cyber Aces'/               Finance/                         myoutput.txt       mytestplayfile   README/
 13-Elk-Stack-Project_Resources_README.zip  'Brian To Do List 08 05 20.docx'          'Cybersecurity Bootcamp'/   GitHub/                          myoutput.txt.doc  'Play Files'/    'The Linux Command Line.pdf'

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian
$ cd 13-Elk-Stack-Project_Resources_README

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README
$ ls
__MACOSX/  README/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README
$ cd README/

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ ls
Images/  README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ nano README.md

Brian & Katie@DESKTOP-ITJ6OK4 MINGW64 ~/Desktop/Brian/13-Elk-Stack-Project_Resources_README/README
$ cat README.md
## Automated ELK Stack Deployment

The files in this repository were used to configure the network depicted below.

(../GitHub/ELK-Stack-Project/Diagrams/ELK_Project_Diagram.drawio)

These files have been tested and used to generate a live ELK deployment on Azure. They can be used to either recreate the entire deployment pictured above. Alternatively, select portions of the _____ file may be used to install only certain pieces of it, such as Filebeat.

(../GitHub/ELK-Stack-Project/Ansible/install_elk_yml)

This document contains the following details:
- Description of the Topologu
- Access Policies
- ELK Configuration
  - Beats in Use
  - Machines Being Monitored
- How to Use the Ansible Build


### Description of the Topology

The main purpose of this network is to expose a load-balanced and monitored instance of DVWA, the D*mn Vulnerable Web Application.

Load balancing ensures that the application will be highly available, in addition to restricting unauthorized access to the network.
Load balancing plays an important security role by protecting servers against DDoS attacks.  Jump boxes are a valuable tool in load balancing and security. Jump boxes are virtual and by limiting the lines of access to the jump box via ssh channels your servers and network are much more secure._

Integrating an ELK server allows users to easily monitor the vulnerable VMs for changes to the files and system configuration.
Filebeat is a service that monitors log files that you specify, collects log events and forwards to Elasticsearch or Logstash for further analysis._
Metricbeat is a service that collects metrics from the operating system and from other services running on the server. These metrics are then forwarded to either Elasticsearch or Logstash for further analysis._

The configuration details of each machine may be found below.


| Name     | Function | IP Address | Operating System |
|----------|----------|------------|------------------|
| jump-box-provisioner | Gateway | 10.0.0.4 | Linux   |
| Web1     | DVWA Web Server | 10.0.0.7 | Linux       |
| Web2     | DVWA Web Server | 10.0.0.8 | Linux       |
| ELK-VM   | ELK Server      | 10.1.0.4 | Linux       |

### Access Policies

The machines on the internal network are not exposed to the public Internet. Only the local machine can accept connections from the Internet. Access to this machine is only allowed from the following IP addresses:
66.41.201.138.  Machines within the network can be accessed only by ssh through the jump-box-provisioner virtual machine. The ELK-VM allows http traffic only from my local machine's IP address through port 5601.
Only the jump-box-provisioner virtual machine can access the ELK-VM via ssh connection. The Public IP for jump-box-provisioner is 20.55.80.105.

A summary of the access policies in place can be found in the table below.

| Name     | Publicly Accessible | Allowed IP Addresses |
|----------|---------------------|----------------------|
| jump-box-provisioner | No | 66.41.201.138 |
| Brian-Red-Team-Security Vnet | No | 23.101.136.62 |

### Elk Configuration

Ansible was used to automate configuration of the ELK machine. No configuration was performed manually, which is a more efficient way of managing configuration allowing admins to focus efforts elsewhere.

The playbook implements the following tasks:
- Configure the machine with docker.
- Install docker.
- Download image sebp/elk:761.
- Activate ports 5601, 9200, and 5044.

The following screenshot displays the result of running `docker ps` after successfully configuring the ELK instance.
(../GitHub/Images/docker_ps_output.png)

### Target Machines & Beats
This ELK server is configured to monitor the following machines:
10.0.0.7
10.0.0.8

We have installed the following Beats on these machines:
Filebeat
Metricbeat

These Beats allow us to collect the following information from each machine:
Filebeat collects log files, captures aggregated data from these logs, and then forwards the logs to either Elasticsearch or Logstash for indexing. From there, the aggregated data can be used to find any changes to files or configurations. For example, we could use it to look for unauthorized login attempts in the event of a DDoS attack.
Metricbeat collects various metrics from the operating system and from other services running on the server and sends this data to Elasticsearch or Logstash for further analysis. For example, we can monitor CPU and Memory performance, inbound and outbound traffic data, and monitor these metrics during penetration testing.

### Using the Playbook
In order to use the playbook, you will need to have an Ansible control node already configured. Assuming you have such a control node provisioned:

SSH into the control node and follow the steps below:
- Copy the install_elk_yml file to your /etc/ansible directory.
- The install_elk_yml playbook should be deployed to your ELK server ip addresses whereas Filebeat and Metricbeat should be deployed to your webservers. Update the hosts file to include the ip addresses of your Web Servers, ELK Server, and assign python3 as the interpreter.
- Run the playbook, and navigate to your ELK Server via ssh to check that the installation worked as expected. Running sudo docker ps should show sebp/elk:761 as the image. Finally, navigate to http://<your_ELK_public_IP>:5601/app/kibana to verify the installation worked properly.

### Specific Commands
To clone the entire repository: git clone https://github.com/sunbri-1/ELK-Stack-Project.git
To add specific files to git staging area: git add <filename>
To post new files to your local git repo: git commit -m 'comment'
To push updates to this repository: git push
