# basic-tomcat-zabbix-template
Basic zabbix template for tomcat

1 - Install and configure zabbix_java_gateway

2 - Enable JMX on tomcat instances

JAVA_OPTS="... -Dcom.sun.management.jmxremote -Dcom.sun.management.jmxremote.authenticate=false -Dcom.sun.management.jmxremote.ssl=false -Dcom.sun.management.jmxremote.port=12345 -Dcom.sun.management.jmxremote.rmi.port=12345 "

3 - Import template and associate instances
