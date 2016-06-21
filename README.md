# HelloWorldAnt
HelloWorldAnt Project

En este repositorio vamos a poner en pratica  los siguientes puntos:

* Crear un proyecto java hello world con Apache Ant para ayudarnos a la compilación y los test.
* Haremos una integración continua con Jenkins

Seguiremos el tutorial oficial de Apache Ant qu esta en:
http://ant.apache.org/manual/tutorial-HelloWorldWithAnt.html

##Creamos el proyecto en el filesystem

'''training@ubuntu-devops:~/devOps/repomartes/src/oata$ more HelloWorld.java 
package oata;

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
