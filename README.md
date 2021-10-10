# Ejercicio 6

Implementa balanceador nginx sobre dos instancias de passwordapi con docker-compose



## Ejecución.

Clonar este repo y ejecutar:

``` docker-compose up ```

levanta el servicio de la api sobre puerto 8080. Por ejemplo sobre localhost se puede verificar el balanceo con la respuesta de ```health```

[http://localhost:8080/health](http://localhost:8080/health)