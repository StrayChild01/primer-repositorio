# Las Pruebas
Este es un repositorio donde voy a poner todas las pruebas que necesite hacer.

A ver qué tal se pone esto. ¿Y hoy?

```r
En R:
datosNiños<-c(6, 7, 7, 8, 8, 8, 8, 9, 9, 9, 9, 9, 9, 9, 10, 10, 10, 10, 10, 11)

#R no tiene una funcion para obtener la moda
> obtenerModa <- function(v) {
+     uniqv <- unique(v)
+     uniqv[which.max(tabulate(match(v, uniqv)))]
+ }

> obtenerModa(datosNiños)
[1] 9

> median(datosNiños)
[1] 9

> sum(datosNiños)
[1] 176

> mean(datosNiños)
[1] 8.8

> quantile(datosNiños)
  0%  25%  50%  75% 100% 
   6    8    9   10   11 	
   
> 10-8
[1] 2

> sd(datosNiños)
[1] 1.239694

> sd(datosNiños)**2
[1] 1.536842


```
