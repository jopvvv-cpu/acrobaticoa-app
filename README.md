# AcrobáticoA

Editor de PDF para los documentos del colegio, con un pequeño acróbata que da un mortal hacia atrás cada vez que guardas.

Es un único archivo, `index.html`, que funciona en el navegador. El PDF no se sube a ningún sitio: todo se procesa en tu ordenador.

## Cómo usarlo

1. Descarga `index.html` y ábrelo con Chrome, Edge o Firefox (necesita conexión a internet para cargar las librerías).
2. Pulsa **Abrir** o arrastra un PDF a la ventana. También puedes pulsar **Nuevo** para empezar una hoja A4 en blanco, o **Probar con una ficha de ejemplo**.
3. Edita y pulsa **Guardar con voltereta**. Se descarga `tu-archivo-editado.pdf`.

## Instalarla en Windows (para que salga en «Abrir con»)

1. Entra en la dirección de GitHub Pages: `https://jopvvv-cpu.github.io/acrobaticoa-app/` con Chrome o Edge.
2. Pulsa el botón **Instalar** de la barra de arriba (o el icono de instalar en la barra de direcciones).
3. Ahora, al hacer clic derecho en un PDF › **Abrir con**, aparece **AcrobáticoA**. Puedes marcarla como **Siempre**.

Una vez instalada, también abre sin internet.

## En el celular

- **Android (Chrome):** abre la dirección › menú ⋮ › **Instalar aplicación**.
- **iPhone (Safari):** abre la dirección › **Compartir** › **Agregar a inicio**.
- Con **Ver** te desplazas con un dedo. Con cualquier otra herramienta, un dedo dibuja y **dos dedos desplazan** el documento.
- El botón **Páginas** abre el organizador (ordenar, girar, quitar).
- Al guardar puedes **Descargar** o **Compartir** (WhatsApp, correo, Drive o «Guardar en Archivos» en iPhone).

## Privacidad

Publicar la aplicación solo publica el programa. Los PDF que abres se quedan en tu ordenador: no se suben a GitHub ni a ningún servidor. No guardes documentos dentro de esta carpeta del proyecto.

## Herramientas

| Herramienta | Qué hace | Atajo |
|---|---|---|
| Combinar | Junta varios PDF y fotos (JPG, PNG) en un solo PDF, en el orden que elijas. Cada foto ocupa una página A4 | |
| Ver | Desplázate por el documento con el dedo sin dibujar (herramienta inicial en el celular) | |
| Mover | Selecciona lo que añadiste para moverlo, cambiar su tamaño (cuadrito de la esquina), su color, letra o tamaño. Doble clic en un texto para corregirlo. Supr lo borra | V |
| Lápiz | Dibujo a mano alzada | P |
| Texto | Clic donde quieras escribir; Enter para terminar, Mayús+Enter para otra línea. Letra Helvetica, Times o Courier, en negrita (N) o cursiva (K) | T |
| Resaltar | Arrastra para marcar en amarillo | R |
| Caja | Rectángulo con borde | |
| Corrector | Tapa con blanco (lo de debajo sigue en el archivo) | |
| Firma | Dibuja tu firma una vez y colócala con un clic | |
| Imagen | Pon un logo, sello o foto dentro de la página | |
| Censurar | Recuadro negro que **borra de verdad** lo de debajo al guardar (esa página se guarda como imagen) | |
| Recortar | Arrastra para dejar solo una parte de la página; un clic sin arrastrar quita el recorte | |
| Formularios | Si el PDF trae casillas, se rellenan haciendo clic en ellas | |
| Organizar páginas | En las miniaturas: ↑ ↓ para cambiar el orden (o arrastrarlas), ↻ para girar, ✕ para quitar | |
| Deshacer | | Ctrl+Z |
| Guardar | | Ctrl+S |

## El toque acrobático

- El acróbata del logo y la «A» final dan un mortal hacia atrás al abrir y al guardar.
- Las páginas entran girando como en un trapecio.
- En la pantalla de inicio el acróbata hace la rueda sin parar.

## Limitaciones

- No convierte Word directamente: en Word usa **Archivo › Guardar como › PDF** y añade ese PDF en **Combinar**.

- No modifica el texto original del PDF: para cambiarlo, tápalo con el **Corrector** y escribe encima con **Texto**. Para ocultar datos privados usa **Censurar**, no el Corrector.
- No abre PDF protegidos con contraseña.
- El texto usa Helvetica; admite tildes y ñ, pero los emojis se guardan como «?».

Hecho con [pdf.js](https://mozilla.github.io/pdf.js/) y [pdf-lib](https://pdf-lib.js.org/).
