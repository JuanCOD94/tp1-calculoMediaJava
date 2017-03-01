# tp1-calculoMediaJava #
Aplicación Java que realiza el cálculo de media de 3 varibables enteras. 


----------
### Requisitos ###

Se requiere la última actualización de Java, que contiene la JVM para que la aplicación sea lanzada.
Requiere la instalación de Maven para construir el proyecto.

----------
### Instalación ###

 1. Clonar el repositorio
 
        git clone https://github.com/Juandelsal/tp1-calculoMediaJava.git
 
 2. Una vez descargado el repositorio, puede realizar cambios en la aplicación antes de compilar el .jar (véase configuración, más abajo). La ruta del  .java es:
    
        /tp1-calculoMediaJava/src/main/java/ProyectoTP1/CalculoMedia/CalculoMedia.java
    
 3. Una vez se ha configurado, creamos la carpeta /target utilizando el siguiente comando que nos proporciona Maven:
 
        mvn package
 
 4. Una vez construida con éxito la carpeta /target, dentro de ella ejecutamos la aplicación:
        
        java -cp CalculoMedia-0.0.1-SNAPSHOT.jar ProyectoTP1.CalculoMedia.CalculoMedia

----------
### Configuración ###

Para editar los datos double:

    double a=x;
    double b=x;
    double c=x;

----------
### Licencia ###

Lee el file "LICENSE" por favor.
