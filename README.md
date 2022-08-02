# Make Health Colombia 2022

http://makehealthlatam.com/

## Workshop: Introducción a la estandarización de registros médicos electrónicos para la analítica y la Inteligencia Artificial

Este repositorio hace parte del material en el workshop ofrecido en Make Health Colombia 2022


**Descripción**: En este workshop vamos a ver cómo podemos estandarizar registros médicos electrónicos garantizando interoperabilidad semántica a través de ontologías y vocabularios controlados. Así mismo veremos cómo podemos entrenar un modelo predictivo en menos de una hora utilizando herramientas libres y abiertas gracias a la estandarización de los datos. Veremos el paso a paso de como utilizar ATLAS Daremos una introducción al modelo de datos OMOP-CDM y las herramientas de software libre y abierto de la comunidad OHDSI.

**Objetivos:**

1. Conocer el modelo de datos OMOP-CDM para la estandarización de registros médicos electrónicos.

2. Explorar el uso de herramientas de software libre y abierto para la creación de modelos predictivos.

3. Analizar el impacto de la estandarización y el software libre y abierto para la creación, el despliegue y el uso de modelos predictivos en aseguradoras e instituciones prestadoras de salud.

## Docker Container

Si te interesa correr localmente RStudio despues del tutorial lo puedes hacer corriendo el siguiente comando. Solo debes substituir `<directorio_local>` por una ruta en tu computador en la que quieras guardar el trabajo realizado.

Puedes encontrar mas informacion acerca de como instalar Docker en tu computador en este [link](https://www.docker.com/get-started/)

`docker run -d --net=host -e USER=ohdsi --restart always -e PASSWORD=ohdsi -v <directorio_local>:/home/ohdsi/workdir odysseusinc/rstudio-ohdsi:latest`
