FROM tomcat

#Descargar driver de postgres y copiar en la ruta de librerias de tomcat
ADD https://jdbc.postgresql.org/download/postgresql-42.3.4.jar /usr/local/tomcat/lib/

#Copiar la aplicacion en webapps

COPY demoHa.war /usr/local/tomcat/webapps/