# Duodécima semana, comienza el 3 de Diciembre

Conviene ir cubriendo los objetivos de la semana, para que la entrega de la práctica no nos pille desprevenidos.

## Objetivos de la semana

2. Trabajar con proveedores en la nube y apreciar los parecidos y
   diferencias con los locales. 

3. Entender los conceptos de los servicios en la nube.

4. Entender el concepto de provisionamiento.

## Otros objetivos

1. Revisar errores comunes en el hito 4.
   1. La aplicación debe ejecutarse siempre de la misma forma: en
      heroku.yml, en el CMD del Dockerfile, en el Procfile.
   2. La aplicación debe seguirse completando, no sólo la
   infraestructura.
	   1. Las rutas se deben testear también.
	   2. Los objetos de una clase no pueden inicializarse todos desde una constante o un fichero, deben usar su constructor para ello.
   3. Errores en la creación del Dockerfile. 
      1. Justificar la imagen base que se usa.
      2. Tener claro qué ficheros son necesarios para el despliegue, y
         copiar sólo esos. Usar .dockerignore o simplemente copiar
         sólo lo que haga falta.
    4. Errores en el diseño de la aplicación REST
	  1. Poner métodos GET y PUT sin tratarlos de forma diferente.
	  2. No poner más que métodos GET. Para añadir información, se debe usar PUT
      3. Usar métodos GET para cambiar el estado del servidor. Para ello se deben usar todos menos este.
	  4. Diseño de rutas arbitrario y como nombre de funciones. Se deben diseñar alrededor del nombre del recurso al que se accede, que puede ser el mismo nombre de la clase.
	  

1. Instalar clientes de servicios en la nube.

2. Entender temas de seguridad de la información relacionados con los
   servicios en la nube.

3. Hacer pruebas de provisionamiento de servicios en la nube. 

## Material para la clase

Tema dedicado a
[uso de sistemas](http://jj.github.io/IV/documentos/temas/Uso_de_sistemas). Se
continúa con el 
[último hito](http://jj.github.io/IV/documentos/proyecto/5.IaaS). Recordatorio: fecha de entrega **21 de diciembre**. 


## Siguiente semana

[Decimotercera semana](13-semana.md). 
