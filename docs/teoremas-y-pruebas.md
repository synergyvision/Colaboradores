# Guía para Colaboradores
Synergy Vision  
`r Sys.Date()`  

# Prefacio {-}

Placeholder


## ¿Por qué  leer este libro? {-}
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

\mainmatter

# Introducción 

En el presente material encontrarán el como suscribirse a Git, luego se indicará paso a paso como hallar un repositorio dentro de GitHub, clonar el archivo para poder manipularlos en RStudio.

Una vez clonados los archivos se indicará como modificarlos, realizar commit paso a paso acerca de los cambios realizados, subir y bajar los cambios que esten ubicados en la nube.

Además se demuestra como trabajar en Bookdown de forma detallada.

Cabe destacar que cada colaborador tendrá un repositorio con las fuentes necesarias para generar su libro.



<!--chapter:end:010-introduction.Rmd-->


# Git y Bookdown 

Placeholder


## ¿Cómo suscribirte a Git?
## Encontrar repositorio en GitHub
## Clonar repositorio en RStudio
## ¿Cómo trabajar en bookdown?
## Errores comunes 

<!--chapter:end:020-git.Rmd-->

# Teoremas y pruebas

Los teoremas y pruebas se utilizan comúnmente en artículos y libros en matemáticas. 
En bookdown, los tipos de entornos de teorema admitidos se encuentran en la siguiente tabla para escribir un teorema, puede usar la siguiente sintaxis:

` ```{theorem} `

` Aquí está mi teorema `

` ``` `

| Environment | Printed Name | Label Prefix |
|:-----------:|:------------:|:------------:|
|   theorem   |    Teorema   |      thm     |
|    lemma    |     Lemma    |      lem     |
|  corollary  |   Corolario  |      cor     |
| proposition |  Preposición |      prp     |
|  conjecture |   Conjetura  |      cnj     |
|  definition |  Definición  |      def     |
|   example   |    Ejemplo   |      exm     |
|   exercise  |   Ejercicio  |      exr     |


Para escribir otros entornos de teorema, reemplace ` ```{teorema} ` con otros nombres de entorno como se mostró en la tabla anterior, por ejemplo,` ``` {lemma} `.

Un teorema puede tener una opción de nombre para que su nombre se imprima, por ejemplo,

` ```{theorem, name="Teorema de Pitágoras"} `

` Para un triángulo rectángulo, si $ c $ denota la longitud de la hipotenusa `

` y $ a $ y $ b $ denotan las longitudes de los otros dos lados, tenemos `

` $$ a ^ 2 + b ^ 2 = c ^ 2 $$ `

` ``` `

\BeginKnitrBlock{theorem}\iffalse{-91-84-101-111-114-101-109-97-32-100-101-32-80-105-116-225-103-111-114-97-115-93-}\fi{}<div class="theorem"><span class="theorem" id="thm:unnamed-chunk-1"><strong>(\#thm:unnamed-chunk-1)  \iffalse (Teorema de Pitágoras) \fi{} </strong></span> Para un triángulo rectángulo, si $ c $ denota la longitud de la hipotenusa
 y $ a $ y $ b $ denotan las longitudes de los otros dos lados, tenemos
 $$ a ^ 2 + b ^ 2 = c ^ 2 $$ </div>\EndKnitrBlock{theorem}

Para hacer una referencia sobre el teorema se debe colocar label=nombre que se le quiera colocar al teorema.

` ```{theorem, label="foo"} `

` Este es mi teorema  `

` ``` `

\BeginKnitrBlock{theorem}<div class="theorem"><span class="theorem" id="thm:foo"><strong>(\#thm:foo) </strong></span>
Este es mi teorema
</div>\EndKnitrBlock{theorem}

Para hacer referencia utilizando label se hace con el comando `\@ref(prefix:label)`, en este caso el prefix=thm que corresponde a teorema.  Para utilizar el ejemplo antes descrito colocamos label=foo.

` \@ref(thm:foo)`

\@ref(thm:foo)

<!--chapter:end:030-teorema-pruebas.Rmd-->


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

