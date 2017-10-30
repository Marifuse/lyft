# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/lyft.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto:

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza la tipografía `Montserrat`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes:

  - Botones, hover: `#FF00BF`
  - Fondo de `footer`: `#333447`
  - Título del formulario: `#352384`
  - Texto del formulario: `#728099`
  - Gradiente morado: `linear-gradient(#76278F, #2B1E66);`

* Para el footer, deberás tomar en cuenta que tiene un hover y se ve como en la
  siguiente imagen:

  ![Lyft - Footer](docs/footer.gif)

  Además, los íconos deberás obtenerlo de `Icomoon`.

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios, videos de Youtube). No te preocupes, estamos seguros
  que los afrontarás con éxito, de igual forma aquí unos tips:

  - Estos son los videos de Youtube:
    * https://www.youtube.com/watch?v=fLSmUWOYpKw
    * https://www.youtube.com/watch?v=V7j8Aqxmbs8
    * https://www.youtube.com/watch?v=xj2VWLV0xCU
  - Para agregar los videos, averigua sobre la etiqueta `iframe`.
  - Para el formulario, revisa las etiquetas como `form` e `input`.

* Puedes ver el [sitio original](https://www.lyft.com/), sin embargo, su diseño
  ya ha cambiado en ciertas partes, así que tu fuente de verdad es la imagen que
  muestra el objetivo de este reto.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Estructura de carpetas y archivos
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible

***

## README DE TRABAJO LYFT

* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

## Especificaciones del Proyecto

El proyecto venía con una base forkeable de _GITHUB_, el cual, debía ser modificado para hacer una réplica de la página original
enlazada en este README.

El contenido de la carpeta trae:
* _UN README_

* _UNA CARPETA CON IMÁGENES_

* _LA CARPETA CSS (Uno de los formatos que se debía trabajar)_

* _UNA CARPETA DOCS_

* _UNA CARPETA FONTS_

* _EL INDEX.HTML (el otro formato que se debía trabajar)_

***

## Ejecución de la Página

Para que se pueda ejecutar el proyecto, se debieron seguir los siguientes pasos:

**HTML**

* Enlazar por medio de la etiqueta LINK el formato CSS al fotmato HTML, junto con la carpeta de los íconos.
* Modificar el HTML con los textos e imágenes que venían en la carpeta forkeada (Esto se logra dividiendo en secciones cada parte de la
página, uso de cierre o FOOTER, uso de etiquetas, forularios, usar clases, usar íconos, entre otros).
* Enlazar igualmente al HTML los tipos de fuentes que e van a utilizr en la página (Google Fonts), también por medio de la 
etiqueta LINK.

**CSS**

* Comenzar el trabajo por secciones, desde lo más general a lo más particular para darle estilos (Modificación de las fuentes, tamaños
de imágenes y letras, colores de fondo y de letras, dar colores y formas a los íconos, dar estilo a los input y buttons, entre otros).
* Llamar por clases Padre o Hijo en caso de ser necesario para no generar conflictos.
* Dejar comentarios separando las secciones que se están trabajando.

***

## Limitaciones y dificultades

* Falta de llamado a las clases en algunas etiquetas, los cuales, generaron inconvenientes en la HOJA DE ESTILOS puesto que cambiaba a
nivel general y no particular.
* La lentitud de carga por los videos.
* No se pudo generar la otra barra blanca, ya que para eso se necesita funciones JS.
* Esta página es sólo un trabajo replica, el cual, no tiene funciones JS (Maquetado).
