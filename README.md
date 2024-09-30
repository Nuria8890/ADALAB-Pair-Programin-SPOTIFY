# ADALAB-Pair-Programin-SPOTIFY

  - Enlace donde está el diseño para las diferentes versiones de dispositivos: <https://github.com/Adalab/ejercicios-de-los-materiales/tree/main/html-spotify>

## 1.1 Mi primera página web
  - La distribución de elementos de la página tiene que estar perfecta.
  - OK El repositorio de GitHub se tiene que llamar: **promo-A-module-1-pair-1-spotify.**
  - OK Crea la estructura de carpetas adecuada para tu proyecto con HTML y CSS.


## 1.2 Modelo de caja y herramientas
  - Es importante entender cómo se comportan las etiquetas cuando les cambiamos propiedades de apariencia como *margen, borde, padding y ancho/alto*.
  1. Crea todo el contenido y etiquetas del HTML.
  2. OK Crea una hoja de estilo de reset.
  3. OK Identificar qué grupos de elementos se comportan como un único elemento para agruparlos en el código (<div>) y darle estilos en conjunto.
  4. Añadir clases de CSS: `.my-container { border: solid 3px red; background: blue}` y poner estilos de borde y background (luego borrar) para visualizar todos los bloques de contenido.
  5. **Cabecera**: aplicar estilos a la imagen y al menú. Fondo negro y letra blanca. Alinear el menú de la cabecera en línea y hacia la derecha (franja negra). Fuente `Roboto`.
  6. Identificar valor repetidos para ponerlos en el root como variables.

  ## 1.3 Flexbox
  - Se usa para hacer:
    - Pie de página fijo
    - Panel lateral con una parte fija y otra flexible.
    - Menú horizontal.
    - Listado de iconos de redes sociales.
    - Noticia donde la imagen esté arriba o detrás del texto.
  
  1. Modificar elementos hijos de la cabecera:
    - La parte azul (el hero) debe medir de alto el `50% del alto de la ventana`.
  2. Maquetar la sección de los beneficios, que tiene título *¿Por qué pasarte a premium?* --> ¿se debe distribuir de forma diferente para cada dispositivo?
    - Aplicar estilos para maquetar cada una de las hijas de la sección.
  3. Maquetar el **Footer** usando flexbox.

  ## 1.4 Posicionamiento
  - **Cabecera**: debe ser fija, se mostrará por encima del resto de contenidos cuando se haga_scroll_hacia abajo. ((ejercicio "vente conmigo" 1.4.2))
    - La parte azul se modifica, hay que ajustar lo que corresponda para mantener el diseño.
   
  ## 1.5 Diseño Responsive
  - Crear dos *media queries*: tablet y escritorio.
  - **Cabecera**:
    - Móvil: menú hamburguesa.
    - Otras: se oculta el menú hamburguesa y se muestra el listado del menú.
  - **Sección azúl**:
    - Móvil: la imagen de fondo no existe.
    - Otras: imagen de la chica bailando alineada a la derecha.
  - **Sección blanca**: comprobar cómo se distribuyen los elementos de todos los dispositivos. 
