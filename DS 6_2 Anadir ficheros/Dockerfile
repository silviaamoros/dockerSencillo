FROM jboss/wildfly:10.1.0.Final

ADD https://downloads.mariadb.com/Connectors/java/connector-java-1.5.9/mariadb-java-client-1.5.9.jar /opt/jboss/wildfly/modules/system/layers/base/org/mariadb/jdbc/main/
COPY librerias/module.xml /opt/jboss/wildfly/modules/system/layers/base/org/mariadb/jdbc/main/
ADD aplicacion/Aplicacion.war /opt/jboss/wildfly/standalone/deployments/
