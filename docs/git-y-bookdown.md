# Guía para Colaboradores
Synergy Vision  
`r Sys.Date()`  

# Prefacio {-}

Placeholder


## ¿Por qué  leer este libro? {-}
## Estructura del libro {-}
## Información sobre los programas y convenciones {-}
## Prácticas interactivas con R {-}
## Agradecimientos {-}

<!--chapter:end:index.Rmd-->


# Acerca del Autor {-}

Este material es un esfuerzo de equipo en Synergy Vision, (<http://synergy.vision/nosotros/>).		 

El propósito de este material es ofrecer una experiencia de aprendizaje distinta y enfocada en el estudiante. El propósito es que realmente aprenda y practique con mucha intensidad. La idea es cambiar el modelo de clases magistrales y ofrecer una experiencia más centrada en el estudiante y menos centrado en el profesor. Para los temas más técnicos y avanzados es necesario trabajar de la mano con el estudiante y asistirlo en el proceso de aprendizaje con prácticas guiadas, material en línea e interactivo, videos, evaluación contínua de brechas y entendimiento, entre otros, para procurar el dominio de la materia.
  		  
Nuestro foco es la Ciencia de los Datos Financieros y para ello se desarrollará material sobre: **Probabilidad y Estadística Matemática en R**, **Programación Científica en R**, **Mercados**, **Inversiones y Trading**, **Datos y Modelos Financieros en R**, **Renta Fija**, **Inmunización de Carteras de Renta Fija**, **Teoría de Riesgo en R**, **Finanzas Cuantitativas**, **Ingeniería Financiera**, **Procesos Estocásticos en R**, **Series de Tiempo en R**, **Ciencia de los Datos**, **Ciencia de los Datos Financieros**, **Simulación en R**, **Desarrollo de Aplicaciones Interactivas en R**, **Minería de Datos**, **Aprendizaje Estadístico**, **Estadística Multivariante**, **Riesgo de Crédito**, **Riesgo de Liquidez**, **Riesgo de Mercado**, **Riesgo Operacional**, **Riesgo de Cambio**, **Análisis Técnico**, **Inversión Visual**, **Finanzas**, **Finanzas Corporativas**, **Valoración**, **Teoría de Portafolio**, entre otros.

Nuestra cuenta de Twitter es (https://twitter.com/bysynergyvision) y nuestros repositorios están en GitHub (https://github.com/synergyvision).
  		  
 **Somos Científicos de Datos Financieros**

<!--chapter:end:000-author.Rmd-->


# Introducción 

Placeholder


## Motivation

<!--chapter:end:010-introduction.Rmd-->

# Git y Bookdown 

## ¿Cómo suscribirte a Git?

Para crear una cuenta en GitHub, ingresamos al enlace: [pulsa aquí para dirigirte a la página https://github.com](https://github.com)

1.- Ingresamos nuestro nombre de usuario, correo electrónico, contraseña y confirmamos contraseña.

2.- Una vez ingresado los datos, opriminos el botón "Create an account".

![ ](images/pant-suscribir-git.png)

## Encontrar repositorio en GitHub

1.- Entrar en GitHub con tu cuenta.

![ ](images/pant-repos.png)

2.- Colocar en el buscador synergyvision/colaboradores.

![ ](images/pant-repos-1.png)




Donde synergy vision representa la organización y colaboradores es el repositorio a descargar.



![ ](images/pant-repos-2.png)

3.- Ubicarse en ![Image](images/pant-clone.png)

4.- Darle un clip y copiar el enlace para luego clonarlo en RStudio 

![ ](images/pant-enlace.png)

## Clonar repositorio en RStudio

1.- Abrir RStudio

![ ](images/pant-rstudio.png)



2.- Colocarse en la barra de herramientas del lado derecho, dar clip a New Project

![ ](images/pant-rstudio-1.png)


3.- Dar clip en Version Control

![ ](images/pant-rstudio-2.png)


4.- Dar clip en Git

![ ](images/pant-rstudio-3.png)


5.- En esta pantalla debes realizar 2 pasos y son los siguientes:

a) Copiar el enlace que traes de GitHub en Repository URL

b) En Project directory name, debe colocar el nombre del proyecto (Colaboradores) sin espacio ni caracteres especiales, prestando atención de la dirección donde se está guardando el proyecto (para ubicaciones futuras).

c) Darle un clip en Create Project.

![ ](images/pant-rstudio-5.png)


## ¿Cómo trabajar en bookdown? {-}

1.- Una vez descargado el repositorio, encontrarán entre los archivos una carpeta que se llama bookdown.

![ ](images/pant-bookdown.png)


2.- En la carpeta bookdown se colocarán los capítulos generados para la creación de cada libro, las imagenes y datos referentes al mismo. Por ejemplo:

![ ](images/pant-bookdown-1.png)


2.1. La numeración consecutiva es para que el archivo index.Rmd relacione los capítulos del libro, en este ejemplo existe un único capítulo que es Git y en él se encuentran todos los pasos que estás leyendo.

Si necesitas crear un nuevo capítulo debes generar un archivo.Rmd colocando una numeración consecutiva como por ejemplo 030-(nombre) y así sucesivamente.

2.2. Los archivoss .yml generan la estructura que tendrá el libro por consiguiente no deben cambiarse.

2.3. La carpeta data debe contener archivos que guarden datos, los cuales pueden llegar a necesitarse para algún ejemplo o ejercicio a desarrollar dentro del libro, ejemplo un archivo.xls.

2.4. La carpeta images es para guardar las imágenes que serán usadas en el libro.

2.5. El archivo 010-introduccion.Rmd debe contener la introducción del libro. El archivo 400-apendice.Rmd, debe contener los apendices del libro y el archivo 500-references.Rmd, debe contener las referencias bibliográficas usadas.


3.- Generación de vista previa, en primer lugar se debe guardar los cambios realizados, luego abrir el archivo index.Rmd para generar la vista orevia del libro y ver los cambios realizados. Se realiza de la siguiente manera







<!--chapter:end:020-git.Rmd-->


# (APPENDIX) Apéndice {-}

Placeholder

# Software Tools

Placeholder


## R and R packages
## Pandoc
## LaTeX

<!--chapter:end:400-apendice.Rmd-->

# Referencias {-}




<!--chapter:end:500-references.Rmd-->

