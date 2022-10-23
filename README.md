# mongo4_tomcat9_debian

This script install on debian mongodb CE version 4.4 and tomcat 9 (9.0.68)

N.B.

Tested with openjdk-17-jdk

To install mongo4_tomcat9_debian run:

ansible-playbook -i hosts site.yaml

To uninstall mongo4_tomcat9_debian run:

ansible-playbook -i hosts deprovision.yaml

Adding Tags to permit run only specific task of playbook

Tags:

upgrade
package
ntp
mongodb
tomcat


For example, to launch only task regarding upgrade os, run:
 
ansible-playbook -vv --tags "upgrade" -i hosts site.yaml
