Este sitio web está construido usando [Docusaurus](https://docusaurus.io/), un generador moderno de sitios web estáticos.

# Cómo contribuir

## Estructura de directorios

```
docs/
  conocimiento-común/
    0-Presentaciones.md
    1-Killer opener.md
    2-Idea de negocio.md
    3-MVP.md
    4-Análisis de costes y TCO.md
    5-Organización del equipo.md
    6-Commitment Agreement.md
    7-Uso de la IA.md
    8-Sprint Retrospective.md
    9-Demo del producto.md
    10-Usuarios piloto.md
    11-Desarrollo del producto.md
    12-Análisis y garantía de la calidad.md
    13-Storyboards.md
    14-Cumplimiento legal.md
  grupos-mañana/
    1-Grupo 1.md
    2-Grupo 2.md
    3-Grupo 3.md
    4-Grupo 4.md
    5-Grupo 5.md
    6-Grupo 6.md
  grupos-tarde/
    1-Grupo 7.md
    2-Grupo 8.md
    3-Grupo 9.md
    4-Grupo 10.md
    5-Grupo 11.md
```

## Cómo añadir feedback individual
Cada grupo tiene su propio archivo markdown en la carpeta correspondiente (dependiendo si el grupo es de la mañana o de la tarde). Los archivos markdown contienen el feedback interno (el feedback interno corresponde al feedback recogido por el propio equipo de trabajo) recogido por cada grupo durante las sesiones de clase. Con secciones para cada semana, se detallan los comentarios y sugerencias del profesor y los compañeros, así como las tareas a realizar para la siguiente semana. Además, se incluye una sección para el resto de grupos con el feedback proporcionado por parte de dicho grupo.

## Cómo añadir feedback grupal
El feedback grupal se recoge en el archivo markdown de la carpeta conocimiento-común. En este archivo se recoge el feedback común proporcionado por el profesor y los compañeros relativo a diferentes aspectos como la organización del equipo de trabajo, las presentaciones, la gestión de usuarios piloto, etc. 

Para incluir información en este archivo, es necesario trabajar en la rama feedback-grupal y mantener dicha rama actualizada con regularidad.

## Despliegue en local
Para desplegar el sitio web en local, sigue los siguientes pasos:
1. Clona el repositorio en tu máquina local.
```
git clone git@github.com:ISPP-2425/BCC.git
```
2. Instala las dependencias necesarias.
```
cd BCC
npm install
```
3. Inicia el servidor de desarrollo.
```
npm start
```
4. Desde la dirección [http://localhost:3000](http://localhost:3000) podrás acceder al sitio web y comprobar los cambios realizados a tiempo real en tu máquina local.

## Cómo subir los cambios a GitHub
Con el objetivo de evitar conflictos al subir los cambios a GitHub, se recomienda seguir los siguientes pasos:
- Trabajar en la rama correspondiente al grupo de trabajo o en la rama común (feedback-grupal).
- Hacer una solicitud de pull request a la rama principal (main) de este repositorio.
- Esperar a que la pull request sea revisada y aprobada por el administrador del repositorio.

En caso de que se produzcan conflictos durante la creación de la pull request, se recomienda contactar con el administrador del repositorio [Angelgares](https://github.com/Angelgares) para su resolución.

## Despliegue automático
Este repositorio está configurado para desplegar automáticamente los cambios en la rama principal (main) a través de [Vercel](https://vercel.com/). Por lo tanto, una vez que se haya hecho el pull request a la rama principal, los cambios se desplegarán automáticamente en la siguiente dirección: [Base de Conocimiento Común](https://bcc2425.vercel.app)
