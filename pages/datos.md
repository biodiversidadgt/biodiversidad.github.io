---
layout: page-fullwidth
title: "Datos de Biodiversidad"
subheadline: "Generalidades"
teaser: "Información general acerca de datos de biodiversidad."
permalink: "/datos/"
header:
   image_fullwidth: "header_pluma.jpg"
---

<div class="row">
<div class="medium-4 medium-push-8 columns" markdown="1">
<div class="panel radius" markdown="1">
**Tabla de Contenido**
{: #toc }
*  TOC
{:toc}
</div>
</div><!-- /.medium-4.columns -->

<div class="medium-8 medium-pull-4 columns" markdown="1">

---

## Datos de Biodiversidad   {#datos-biodiversidad}

Los datos de biodiversidad provienen de registros de organismos en un tiempo y un espacio definido. Para hacer estos registros, se necesita evidencia en forma de `especímenes` depositados en colecciones biológicas, o de `observaciones` generalmente respaldadas con imágenes, videos o sonidos. Existen formatos estandarizados para la captura de datos de biodiversidad, incluyendo [Darwin Core](https://www.tdwg.org/standards/dwc/), que contiene los campos necesarios para documentar esta información.    

## Tipos de Registros
El [**Portal de Biodiversidad de Guatemala**](https://biodiversidad.gt) permite el ingreso de `datos de especímenes` en un formato estandarizado (i.e. [Darwin Core](https://dwc.tdwg.org/)), que facilita su manejo e intercambio con otras plataformas de especializadas. Existen tres tipos de `registros de organismos` que pueden ser manejados en el Portal bajo estos estándares. La clasificación de los registros depende del origen y forma de respaldo de la información.

### Registros de especímenes preservados

Es el principal tipo de datos manejados dentro del Portal de Biodiversidad. Estos registros consisten en información contenida en `etiquetas de especímenes` depositados en colecciones científicas (plantas, animales, hongos, fósiles). Pueden incluir fotografías de los especímenes y/o etiquetas, pero no es requisito para ingresar los datos. [Ejemplo](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=16) de colección de especímenes preservados.

[![image](https://github.com/biodiversidadgt/docs/assets/69399374/d1754118-980e-44c2-b719-2be3575d2eac)
](https://biodiversidad.gt/portal/collections/individual/index.php?occid=8126&clid=0)
Fotografía: Julio Ayala. Colección de Artrópodos UVGC.

### Registros de especímenes vivos

Similares a los registros de especímenes preservados, pero la información proviene de `ejemplares vivos` en colecciones institucionales. Un ejemplo son los jardines botánicos que contienen ejemplares vivos de plantas. Requieren evidencia fotográfica.

### Registros de observaciones

Se refiere a registros esporádicos, realizados al observar un organismo en estado silvestre. Requieren de evidencia fotográfica, ya que los organismos no son capturados. Actualmente, Symbiota no maneja otro tipo de archivos multimedia como videos o sonidos. [Ejemplo](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=8) de colección de especímenes vivos.

[![image](https://github.com/biodiversidadgt/docs/assets/69399374/0c493177-cf6d-4f84-bee1-e601a093df33)
](https://biodiversidad.gt/portal/collections/individual/index.php?occid=7672&clid=0)
Fotografía: María José Chang. Colección Fotográfica UVGF.

---

## Tipos de Perfiles Virtuales   {#perfiles}

El Portal de Biodiversidad de Guatemala permite la generación de perfiles virtuales individuales para el manejo independiente de colecciones. Cada perfil cuenta con un formulario y herramientas especializadas para el ingreso y manejo de datos, así como opciones de configuración que va a permitir distintos niveles de acceso, para una eficiente organización de las tareas de digitalización por parte de encargados, investigadores y estudiantes. 

[![PerfilUSCG](https://github.com/biodiversidadgt/docs/assets/69399374/070a86f6-2d7f-4703-a0f3-80a58b76ca83)
](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=69)
`Perfil virtual de la Colección de Hongos del Herbario USCG CECON de la USAC.`

Existen dos tipos de perfiles virtuales que pueden ser solicitados en el Portal de Biodiversidad, dependiendo del manejo que se le quiera dar a los datos.

### Perfiles en vivo

Los perfiles en vivo van a permitir el `manejo directo de los datos` dentro del Portal de Biodiversidad. Los administradores de estos perfiles tienen acceso a todas las herramientas de edición disponibles dentro del Portal de Biodiversidad. Todas las colecciones de instituciones guatemaltecas manejadas actualmente en el Portal de Biodiversidad poseen perfiles de manejo en vivo. [Ejemplo](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=21) de colección manejada en vivo.

### Perfiles snapshot

Los perfiles snapshot (imágenes) van a ser `copias de bases de datos existentes` en otras plataformas, y sólo van a permitir la publicación de los datos en el Portal, sin posibilidad de realizar ediciones. Los curadores que prefieren este tipo de perfiles, ya cuentan con un sistema de manejo de colecciones local. Los perfiles de instituciones extranjeras y los perfiles de observaciones de iNaturalist, cuentan con un manejo externo y únicamente se cuenta con perfiles snapshot en el Portal de Biodiversidad. [Ejemplo](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=56) de colección snapshot.

---

## Tipos de Permisos en los Perfiles Virtuales

Únicamente los curadores pueden solicitar la generación de un perfil de colección, y son agregados automáticamente como administradores del perfil. Sin embargo, existe la posibilidad de agregar más usuarios en los perfiles, con distintos tipo de acceso.

### Administradores del perfil

Tienen acceso a todas las funciones de ingreso y edición de datos. Los administradores, además, pueden otorgar permisos a otros usuarios, eliminar registros, y editar la información de la colección.

![PerfilUSCGadmin](https://github.com/biodiversidadgt/docs/assets/69399374/c932cb52-d917-4b1a-81d2-c84ea322d5e8)
Perfil virtual visto por un administrador, con todas las herramientas activadas.

### Editores del perfil

Tienen acceso a todas las funciones de ingreso y edición de datos. No pueden otorgar permisos a otros usuarios, ni editar la información de la colección.

![PerfilUSCGeditor](https://github.com/biodiversidadgt/docs/assets/69399374/f1956e6f-9d5e-4c63-af79-025071df11ca)
Perfil virtual visto por un editor, únicamente con el panel respectivo activado.

---

## Solicitar un Perfil Virtual en el Portal de Biodiversidad

Los curadores o encargados de las colecciones pueden solicitar uno o varios perfiles virtuales para sus colecciones, una vez hayan evaluado el tipo de datos que poseen (i.e. especímenes u observaciones) y el tipo de manejo que quieren utilizar (i.e. manejo en vivo o snapshot).

Con una [cuenta activa](https://biodiversidad.gt/portal/profile/newprofile.php), los curadores pueden solicitar la creación del perfil de la colección a los [administradores del portal](https://biodiversidadgt.github.io/docs/contactos/), enviando la siguiente información:

- Nombre y acrónimo de la universidad o institución.
- Nombre, acrónimo y descripción de la colección.
- Nombre y contacto del curador.
- Tipo de perfil que desea generar (manejo directo o snapshot).
- Tipo de registros que desea manejar (especímenes u observaciones).
- Una vez generado el perfil, el solicitante será añadido como administrador del perfil y podrá iniciar con el ingreso de datos.

</div><!-- /.medium-8.columns -->
</div><!-- /.row -->
