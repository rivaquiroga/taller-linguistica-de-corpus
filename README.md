# (Micro)taller sobre Lingüística de Corpus usando R


## Preparación: instalación de R y RStudio

En este taller utilizaremos el lenguaje de programación R a través del IDE RStudio. IDE es el acrónimo de *Integrated Development Environment* (*Entorno de Desarrollo Integrado*). Esto quiere decir que RStudio es una aplicación que nos entrega herramientas para hacer más fácil el desarrollo de proyectos usando R.

Para poder instalar R y RStudio, sigue los siguientes pasos:

- Descarga R desde https://cran.r-project.org/. Debes elegir la opción que corresponda, según tu sistema operativo.
- Instala R en tu computador, tal como lo haces con cualquier programa.
- Una vez que R ha quedado correctamente instalado, descarga RStudio desde https://www.rstudio.com/products/rstudio/download/. Elige la primera opción, es decir, "RStudio Desktop Open Source License" (gratuita).
- Instala RStudio en tu computador, tal como lo haces con cualquier programa.

Si quedó todo bien instalado, cuando abras RStudio verás algo así (aunque debería decir que es la versión 3.6 de R):

![](https://github.com/rivaquiroga/RLadies-Santiago/blob/master/images/rstudio.png)

En este taller utilizaremos la última versión de R y RStudio, así que si tienes instalada una versión previa, la sugerencia es actualizarla para que todo funcione bien.

### Instalación de paquetes de R que utilizaremos

Cuando instalamos R por primera vez en nuestro computador, lo que estamos instalando es lo que se conoce como "R Base", es decir, los elementos centrales del lenguaje de programación. Una de las ventajas de R es que se trata de un lenguaje extensible: la propia comunidad puede desarrollar nuevas posibilidades para utilizarlo. La manera de compartir estos nuevos desarrollos es a través de "paquetes", que incluyen, entre otras cosas, código y datos. Una analogía que se suele utilizar para explicar esto es que R Base es un teléfono celular tal como viene de fábrica y los paquetes las _apps_ que descargamos para que tenga más funcionalidades.

En este taller utilizaremos tres paquetes. Algunos sirven específicamente para el análisis de textos; otros para el procesamientos y visualización de datos.

Para instalarlos,

1. copia el siguiente código: 

```r
install.packages("quanteda")
install.packages("readtext")
install.packages("tidyverse")
```

2. pégalo en la consola (_Console_) de RStudio:

![](https://github.com/rivaquiroga/RLadies-Santiago/blob/master/images/install.packages.png)

3. presiona 'enter'.
Algunos paquetes son más grandes que otros, por lo que pueden demorar un poco más de tiempo en instalarse.

