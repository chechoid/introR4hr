# introR4hr
## Curso Introducción a R para RRHH

Este paquete contiene tutoriales interactivos del curso **Introducción a R para RRHH** de [Data 4HR](https://data-4hr.com/capacitacion/curso-introduccion-r-para-rrhh/).

Para poder instalar este paquete directamente desde GitHub, primero hay que tener instalado el paquete `remotes`. En el caso que no esté instalado lo podés hacer de la siguiente manera:

```{r eval=FALSE}
install.packages("remotes")
```

Para poder utilizar los tutoriales de este paquete es necesario tener instalado el paquete `learnr`. Si lo necesitás instalar lo podés hacer de la siguiente manera:

```{r eval=FALSE}
install.packages("learnr")
```

Una vez instalado `remotes`, se puede instalar el paquete `introR4hr` copiando y pegando ésta línea de código:

```{r eval=FALSE}
remotes::install_github("chechoid/introR4hr")
```

Este paquete contiene a su vez varios paquetes que utilizaremos a lo largo del curso. Así que es posible que la primera vez que lo instales te pida instalar varios paquetes más, así que si eso ocurre instala todos los paquetes que R te indique (apretando 1 en la consola cuando te lo pida). Puedes ver un video de ayuda en [YouTube](https://youtu.be/6jbeM1T5A20).

## Usar los tutoriales

Ya con todos los paquetes instalados, para poder utilizar un tutorial tenés que correr el siguiente código:

```{r eval=FALSE}
learnr::run_tutorial("sesion0", "introR4hr")
```

-   `"sesion0"` es el nombre del tutorial. Para cada clase utilizar el número de tutorial que corresponda.

-   `"introR4hr"` es el nombre del paquete.

## Inconvenientes, bugs, y esas cosas

Por problemas en el uso de los paquetes, errores en las clases, e inconvenientes que puedan llegar a aparecer con el uso de este paquete podés escribir a

[Sergio Garcia Mora](https://www.linkedin.com/in/sergiogarciamora/) (sergio@d4hr.com).

## Algunas aclaraciones pertinentes

El tono, memes y humor que aplicamos en este paquete de tutoriales está pensado para un grupo de alumnos con el que compartimos una relación y ciertos códigos y chistes en un determinado espacio y tiempo particular. De todas maneras, si algo de lo que publicamos te parece ofensivo por favor escribinos así lo podemos corregir.

## Agradecimientos y créditos

Muchas gracias a [Yanina Bellini Saibene](https://twitter.com/yabellini) y a [Paola Corrales](https://twitter.com/PaobCorrales) :raised_hands: por la ayuda para resolver problemas en el desarrollo de este paquete y en el armado de los tutoriales.

Para más información sobre sus actividades, les recomiendo seguir a [MetaDocencia](https://www.metadocencia.org/)
