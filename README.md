# Documentación en GitHub

Como participante del hackatón *Hello Mexicoders!*, es importante que realices una correcta documentación sobre los proyectos en los que trabajas. No te preocupes si por el momento no cuentas con esta habilidad, pues por medio de esta guía te ayudaré a crear tu primer archivo de documentación.

Para la realización de esta guía se siguen las recomendaciones del artículo “A beginner’s guide to writing documentation”, publicado por la comunidad Write the Docs.

### Tabla de contenidos
* [Introducción a la documentación](#introducción-a-la-documentación)
* [Pasos preliminares](#pasos-preliminares) 
  * [Crear tu cuenta de GitHub](#crear-tu-cuenta-de-github)  
  * [Crear un repositorio](#crear-un-repositorio)
* [Cómo documentar](#cómo-documentar) 
  * [Markdown](#markdown)
  * [Estructura sugerida](#estructura-sugerida)
* [Ventajas de documentar](#ventajas-de-documentar)
* [Referencias](#referencias)

## Introducción a la documentación

La documentación de un proyecto de desarrollo es tan importante como el proyecto mismo. Este tipo de archivos permite transferir el por qué detrás del código, de manera que leer este documento esa suficiente para entender de qué trata o cómo funciona el proyecto. 

Documentar consiste, a grandes rasgos, en **explicar qué hace tu proyecto, cómo y por qué existe**. Como bien señala Write the Docs, es el arte de "asegurarse de brindar a los usuarios toda la información que necesitan, pero no demasiada".[1]

Típicamente este tipo de documentos son la carta de presentación de un proyecto que puede, o no, estar terminado. Debido a ello, es imperativo dejar en claro cómo es que funciona cada elemento o, en su defecto, cómo se desea que funcione.

## Pasos preliminares

### Crear tu cuenta de GitHub

Para crear documentación en GitHub, primero debes tener una cuenta en esta plataforma. Si aún no cuentas con una, puedes crearla gratuitamente [aquí](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home). 

Una vez que inicialices la plataforma con tu cuenta se desplegará una pantalla como la siguiente:
![image](https://user-images.githubusercontent.com/101894380/160957771-ef3ed28e-b09f-4952-9c62-6101e63c76b5.png)


### Crear un repositorio 

Ahora sigue estos pasos para crear tu primer archivo de documentación:

1) Crea un repositorio. Para esto, da click en "Repositories":

![image](https://user-images.githubusercontent.com/101894380/160957948-c8471d4f-87d0-4f8d-b15c-f1366391c160.png) 

2) Ahora da click en "New". 

![image](https://user-images.githubusercontent.com/101894380/160959053-baac65df-2097-4ddc-8f2e-bd821d9c5978.png)

3) Se mostrará una pantalla en la que deberás asignar un nombre al repositorio (preferentemente uno con relación al proyecto que deseas dar seguimiento y documentar). Así mismo, es recomendable llenar el campo de "description". Es **importante** que selecciones las opciones "public" y "Add a README file", pues esto creará el documento README en el que podrás redactar la documentación y será de acceso público (más adelante veremos las ventajas de este tipo de acceso). Después de lo anterior, deberías tener algo así:

![image](https://user-images.githubusercontent.com/101894380/160960485-4ea5faa2-7fa7-43b3-9403-53ba83473e7c.png)

4) Finalmente, da click en "Create repository"

![image](https://user-images.githubusercontent.com/101894380/160960707-52670153-fb93-438f-8972-5547d4e2049c.png)

Ahora que cuentas con tu repositorio, da click en el documento README.md que creaste.

![image](https://user-images.githubusercontent.com/101894380/160964759-0455829c-e007-4de9-98cf-72b6f14d9c8a.png)

Acto seguido presiona el ícono del lápiz y listo, podrás comenzar a redactar tu documentación.

![image](https://user-images.githubusercontent.com/101894380/160965337-1c801cb7-469a-439f-9d90-34fa05d28da8.png)


## Cómo documentar 

### Markdown

Los documentos README.md se editan con escritura tipo Markdown. En este sistema de escritura los párrafos se escriben como comúnmente lo haríamos en cualquier editor de texto, pero los títulos, el uso de negritas, cursiva, links, etc. es diferente.

Aquí un resúmen de cómo escribir en Markdown:

![image](https://user-images.githubusercontent.com/101894380/160968419-6865d7e5-779d-41eb-9b70-09e6b10ba790.png)
Imagen de *Silo Creativo* [2]

En [este link](https://stackedit.io/app#) puedes encontrar un ejemplo de como se ve un texto en formato Markdown y, por ejemplo, cómo se vería una vez que se sube a GitHub. 

### Estructura sugerida

Es importante comenzar por reconocer el público para el que escribes la documentación. Este reconocimiento te ayudará a saber que tan técnica y formal debe ser tu redacción. Así mismo, debes **apremiar la claridad y sencilles**.

Como todo artículo, la documentación comienza por un título; debe ser corto y descriptivo. Inmediatamente después, describe brevemente de qué trata tu proyecto y qué problema resuelve. Anexa una tabla de contenidos en este punto; esto servirá para que las personas que visiten tu repositorio puedan viajar rápidamente dentro de tu documentación.

**Crea enlaces** que redireccionen al usuario a tu código si deseas que otras personas puedan verlo, o incluso modificarlo.

Por ejemplo:

![image](https://user-images.githubusercontent.com/101894380/160977758-93e53f1f-1dc7-4c5a-ac26-4b74ddc7730d.png)

Escribe una pequeña introducción en la que menciones aspectos importantes del funcionamiento de tu proyecto o conceptos con los que quizá no todos estén familiarizados. 

A partir de este punto, la edición debe perseguir el objetivo inicial de la documentación: explicar qué hace tu proyecto, cómo y por qué existe. Para lograrlo procura:

1. Proporcionar la información necesaria para que los usuarios sepan cómo obtener tu proyecto y cómo hacerlo funcionar.
2. Utilizar subtítulos para que los usuarios pueden encontrar más fácilmente lo que buscan.
3. Explicar el funcionamiento típico de tu programa. Los ejemplos son una buena manera de hacerlo.
4. Utilizar imágenes, diagramas.
5. Documentar aspectos del código que generan o podrían generar preguntas frecuentes. 

 

## Ventajas de documentar

En general, documentar nos proporciona muchos beneficios. Entre los principales:

- Funge como una plataforma para realizar constantes contribuciones entre equipos de trabajo.
- La documentación "vende" el proyecto o la idea que se trabaja. Le dice a la gente que este proyecto es para ellos. 
- Funciona como manual de uso.
- El proyecto/código mejora.
- Permite monitorear avances y problemas.
- Desarrolla habilidades de escritura.

El hackatón es un evento en el que principiantes y expertos colaboran para desarrollar software y, el hecho de que los proyectos sobre los que se está trabajando se documenten representa una herramienta colaborativa valiosa.

## Referencias 

[1] Write The Docs, “A beginner’s guide to writing documentation — Write the Docs,” www.writethedocs.org, Jun. 01, 2021. https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/.

[2] A. Serrano, “Qué es Markdown y por qué deberías empezar a usarlo • Silo Creativo,” Silo Creativo, May 12, 2019. https://www.silocreativo.com/que-es-markdown-por-que-deberias-empezar-a-usarlo/ (accessed Mar. 31, 2022).


