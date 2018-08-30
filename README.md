# mongo4_tomcat9_debian9

This script install on debian9 mongodb CE version 4.0 and tomcat 9 (9.0.11)

N.B.

Oracle Jdk it is not installed. The user will have to install it through rpm package or tar.gz ans afterwards setting JAVA_HOME


However this installation of tomcat9 is tested with Oracle Jdk 1.8.0_181
JAVA_HOME has been set in /opt/jdk1.8.0_181


To install mongo4_tomcat9_debian9 on debian 9 run:

ansible-playbook -i hosts site.yaml

To uninstall mongo4_tomcat9_debian9 on debian9 run:

ansible-playbook -i hosts deprovision.yaml
