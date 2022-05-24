La aplicacion inicialmente propuesta no he podido continuarla puesto que la que tenia empezada no compila, y al intentar empezarla de cero me dejaba de compilar
al hacer un par de bindings, te he entregado un proyecto que compila y utiliza retrofit de forma completa, ademas tengo mas material que te podria enseñar mañana 
usando Room y DaggerHilt para gestión de inyección de dependencias, lo que pasa que este ultimo no compila, si pudieras puntuarme algo aunque no sea la actividad 
propuesta te lo agradecería.

En este ejemplo uso Retrofit sobre un modelo llamado Quote que se compone de un json de citas de autores con el formato 
```kotlin 
quote:String author:String
```
Una MainActivity en el que hacemos uso de observers, y una barra de carga que nos indica que esta recogiendo la informacion de internet 
Un ViewModel en el que recogemos los datos mediante corrutinas y de los dos casos de uso creados en el package domain
