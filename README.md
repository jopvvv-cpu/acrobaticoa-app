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

## Privacidad

Publicar la aplicación solo publica el programa. Los PDF que abres se quedan en tu ordenador: no se suben a GitHub ni a ningún servidor. No guardes documentos dentro de esta carpeta del proyecto.

## Herramientas

| Herramienta | Qué hace | Atajo |
|---|---|---|
| Lápiz | Dibujo a mano alzada | P |
| Texto | Clic donde quieras escribir; Enter para terminar, Mayús+Enter para otra línea | T |
| Resaltar | Arrastra para marcar en amarillo | R |
| Caja | Rectángulo con borde | |
| Corrector | Tapa con blanco lo que quieras ocultar o corregir | |
| Firma | Dibuja tu firma una vez y colócala con un clic | |
| Quitar página | Botón en cada miniatura de la izquierda | |
| Deshacer | | Ctrl+Z |
| Guardar | | Ctrl+S |

El color y el tamaño del trazo o del texto se cambian en la barra superior.

## El toque acrobático

- El acróbata del logo y la «A» final dan un mortal hacia atrás al abrir y al guardar.
- Las páginas entran girando como en un trapecio.
- En la pantalla de inicio el acróbata hace la rueda sin parar.

## Limitaciones

- No modifica el texto original del PDF: para cambiarlo, tápalo con el **Corrector** y escribe encima con **Texto**.
- No abre PDF protegidos con contraseña.
- El texto usa Helvetica; admite tildes y ñ, pero los emojis se guardan como «?».

Hecho con [pdf.js](https://mozilla.github.io/pdf.js/) y [pdf-lib](https://pdf-lib.js.org/).
