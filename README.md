# springvetadmin
vetadmin spring

- Requerimientos
  - JAVA 1.8.0_131
  - Apache Maven 3.5.0
  - apache-tomcat-9.0.0.M26
  - Eclipse Oxygen Release (4.7.0)
  
 - Instrucciones
  - agregar java a variables de ambiente
  - definir JAVA_HOME
  - agregar mvn a las variables de ambiente
  - agregar apache tomcat a las variables de ambiente

- Configurar Tomcat en Eclipse
  - Properties (de la app)
  - ir a tab `Runtime`
  - clic en `New`
  - seleccionar apache tomcat 9
  - clic en `Next`
  - clic en `Browse`
  - seleccionar directorio donde se encuentra tomcat, en este ejemplo seria `/Users/claudio/src/JAVA/apache-tomcat-9.0.0.M26`
  - clic en `Abrir`
  - clic en `Finish`
  - clic `Apply and Close`

```sh
PATH="/Library/Frameworks/Python.framework/Versions/3.6/bin:${PATH}"
export JAVA_HOME="$(/usr/libexec/java_home -v 1.8)"
export PATH=/Users/claudio/src/JAVA/apache-maven-3.5.0/bin:$PATH

export CATALINA_HOME=/Users/claudio/src/JAVA/apache-tomcat-9.0.0.M26
export PATH=$PATH:$CATALINA_HOME/bin
```
