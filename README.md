# 🪩 VJSHOW - Generador de Visualizaciones Reactivas

Creada con pasión por **Mediaservi** para la comunidad de VJs, llega VJSHOW. Una herramienta simple, pero increíblemente potente, diseñada para que logres resultados espectaculares y ese "efecto wow" con total facilidad.

Visualiza la música y déjate envolver por un espectáculo de capas reactivas en tiempo real. Úsala desde tu navegador, Smart TV o descárgatela en tu ordenador. Amplifica tus fiestas, eventos y que empiece el VJSHOW. Por fin visuales increíbles que se generan fácil junto con opciones de control y ajuste fino.

🔗 **Pruébala en vivo ahora mismo:**
- **[vjshow.mediaservi.com](https://vjshow.mediaservi.com)**

**Versión actual: v10.2**

🎮 **¿Buscas los juegos?** Ahora tienen su propia web: **[MSGAME · msgame.mediaservi.com](https://msgame.mediaservi.com)**.

## 🚀 Características Clave

- **Audio-Reactividad en Tiempo Real:** Analiza el audio de tu micrófono o sistema y genera visuales sincronizados sin latencia perceptible.
- **Sin Instalaciones (100% Web):** Funciona directamente en el navegador. No requiere licencias caras ni equipos dedicados.
- **Juegos con el móvil como mando:** están en MSGAME, su propia web. El botón «mediaservi GAME SYSTEM» del rack la abre.
- **Soporte Multipantalla y Edge Blending:** Herramientas avanzadas integradas para configurar setups de proyecciones complejas.
- **Fácil y Ajustable:** Una interfaz limpia para arrancar en segundos, pero con parámetros de ajuste fino para los más exigentes.
- **Multiplataforma:** Úsala en tu PC/Mac, lánzala en una Smart TV o instálala como PWA.

## 🛠️ Cómo Funciona

VJSHOW utiliza la Web Audio API y renderizado Canvas/WebGL para procesar las frecuencias de sonido en tiempo real en el lado del cliente (tu navegador). Ningún dato de audio se envía a servidores externos; todo el procesamiento es local, garantizando privacidad y máximo rendimiento.

### Uso Básico:
1. Abre la aplicación en [vjshow.mediaservi.com](https://vjshow.mediaservi.com).
2. Otorga permisos de micrófono o selecciona la entrada de audio de tu sistema (si usas una tarjeta de sonido virtual o mesa de mezclas).
3. Selecciona tus estilos, capas y efectos.
4. Ajusta los controles reactivos y ¡disfruta del espectáculo a pantalla completa!

## 🆕 Cambios de la versión actual (v10.2)

- **Botón «Instalar».** En la cabecera, junto al aviso de fallos, hay un botón nuevo para instalar VJSHOW en el dispositivo como una aplicación más: se abre en su propia ventana, con su icono, y funciona sin conexión con lo que ya se haya usado. Es el mismo botón en toda la familia AVHUB. Donde el navegador no ofrece la instalación directa, el botón explica cómo hacerlo a mano («Añadir a pantalla de inicio»).
- **«Guardar todo para usarla sin internet»**, en esa misma ventana: guarda de una vez toda la app (es el «modo feria» de siempre, ahora más a mano). Y desde la primera visita se guarda ya todo lo que se ha cargado.
- La copia sin conexión es la de siempre (el «modo feria»): la app, las imágenes, los tipos y las librerías. Los vídeos en línea, los efectos de cámara y el enlace del mando siguen necesitando internet.
- No cambia nada más del aspecto ni del funcionamiento.

### Sigue de la v10.1

- **Calibrar el mando, en un solo paso:** se apunta al centro de la pantalla y se pulsa Calibrar. Vale igual para un portátil que para una pantalla gigante. El calibrado fino de tres pasos (centro y dos esquinas) sigue disponible con Mayús+C en el teclado de la pantalla.
- **Corregido:** la segunda pulsación seguida de un mismo botón del mando (Calibrar, Centrar, Play, Stop) se descartaba como repetida. Era la causa de que calibrar pareciera errático.

### Sigue de la v10.0

- **Los tipos del módulo de textos, también en casa.** Las 37 familias libres que usa la capa Texto se sirven desde `fuentes/txt/` (unos 660 KB en total, licencia OFL). VJSHOW ya no pide nada a Google Fonts en ningún momento.
- Solo quedan fuera, y solo cuando se usan: los efectos de cámara (MediaPipe) y el enlace del mando.

### Sigue de la v9.9

- **Librerías y tipos de letra en casa.** three.js, PeerJS y QRCode.js se sirven desde `lib/`, y los tipos de letra fijos de la interfaz y de los juegos desde `fuentes/` (todos con licencia libre: ver `lib/LICENCIAS.md` y `fuentes/LICENCIAS.md`). Al abrir la app ya no se pide nada a Google Fonts, unpkg ni cdnjs.
- No cambia nada del aspecto ni del funcionamiento.

### Sigue de la v9.8

- **Aviso legal:** se añade que es un proyecto personal del autor, ajeno a su empleador, que no lo encarga, financia ni respalda.

Sigue de la v9.7:

- **Solo cambia MSGAME, que comparte código:** logo propio por juego, cartucho con la forma del isotipo y nota de edad recomendada. En VJSHOW no cambia nada.

Sigue de la v9.6:

- **PALOTERAPIA** es el nombre definitivo del juego de cortar y golpear al ritmo (antes HIT HERO).

Sigue de la v9.5:

- **Nombres propios para tres juegos:** **PALOTERAPIA** (antes HIT HERO), **PUNTERÍA** (antes SHOOT HERO) y **GRAFFER** (antes GRAFFITI). Cambian en las cajas, los cartuchos, el menú, el mando y los textos; los juegos son los mismos.

Sigue de la v9.4:

- **Sin nombres ni marcas de otros.** La descripción del juego de cortar al ritmo ya no menciona otro juego; el mensaje de compartir de LA FORTUNA habla de «prize wheel» en inglés; el efecto de texto de VJSHOW se llama «Créditos en perspectiva».
- **Rótulo SONIA con letra propia** (palo seco en cursiva, muy espaciada), grabado y hundido en el plástico del monitor.
- **Tipografía:** los títulos usan solo Audiowide, de licencia libre.
- **Música y efectos:** proceden de Pixabay, bajo su licencia de contenido.

Sigue de la v9.3:

- **Documentación legal completa:** `LEGAL.md`, `DISCLAIMER.md`, `PRIVACY.md` y `COOKIES.md` en el repositorio, enlazados desde el «Aviso legal» de la app. El aviso de la app añade que no es un proyecto técnico ni asesoramiento profesional, que la limitación de responsabilidad no alcanza a lo que la ley no permite excluir, y un apartado de privacidad y contacto.

Sigue de la v9.2:

- **Aviso legal.** Al final de la ventana de ayuda, y enlazado detrás de la línea de crédito, hay un aviso en lenguaje llano (es/en/ca): software gratuito hecho por afición, sin garantías y de uso bajo la responsabilidad de cada cual.

Sigue de la v9.1:

- **Seta roja de aviso de fallos** en la barra de botones: al pasar el cursor explica para qué es; al pulsarla puedes contarnos el fallo y adjuntar capturas.
- **MSGAME (código compartido):** menú del cartucho sin botones en pantalla, variante elegida en la cabecera, monitor sin deformar en móvil vertical, mesa en caoba oscuro y mejoras del mando (calibrado para cualquier tamaño de pantalla, sin música en el móvil).

Sigue de la v9.0:

- **Línea de crédito común** a todas las apps de la familia, con su icono; el texto se cambia desde el panel de administración.
- **ADPOSTER sustituye a NEWS** en el selector de la familia y en el letrero.
- **Mando de MSGAME (código compartido):** si la wifi no deja que el móvil y la pantalla se vean (hoteles, redes de invitados), el mando pasa solo a un enlace de reserva por internet.

Sigue de la v8.9:

- **Solo cambia MSGAME, que comparte código:** la mano coge cada cosa con el brazo saliendo siempre del mismo hombro, y ya no choca con la lámpara. En VJSHOW no cambia nada.

Sigue de la v8.8:

- **Solo cambia MSGAME, que comparte código:** el fondo pasa a ser la foto real del videoclub, difuminada. En VJSHOW no cambia nada.

Sigue de la v8.7:

- **Solo cambia MSGAME, que comparte código:** fondo nuevo, una cafetería de los 50 con suelo de damero y una gramola, difuminada. En VJSHOW no cambia nada.

Sigue de la v8.6:

- **Solo cambia MSGAME, que comparte código:** lámpara de lava luminiscente que pasa por los colores corporativos, walkman tumbado, cubo de Rubik revuelto y lata «6GO». En VJSHOW no cambia nada.

Sigue de la v8.5:

- **Solo cambió MSGAME:** suelo de damero terracota y blanco con la alfombra arcade, todos los juegos a la vista en las baldas de arriba y las cajas tapadas convertidas en decoración que no se puede elegir.

Sigue de la v8.4:

- **El rótulo LED, en reposo,** alterna la firma del pie con una invitación a las otras apps de AVHUB («Prueba también MSGAME: …») y su resumen. Los avisos y la ayuda de cada momento siguen teniendo prioridad.
- **MSGAME, que comparte código, estrena escena:** un solo fondo, estanterías a sangre llenas de juegos, el mismo monitor y la misma consola antes y después de meter el cartucho, el logo oficial grabado, y una lámpara de lava, un walkman y un cubo de Rubik sobre la mesa. En VJSHOW no cambia nada más.

Sigue de la v8.3:

- **Teclas de las otras apps, con más aire.** Hay más separación entre ellas y con el panel de testigos de debajo, y sus logos quedan alineados entre sí por la izquierda, en el centro de cada tecla.
- **El logo oficial, grabado en el chasis.** La placa del frontal lleva ahora el logo oficial de VJSHOW grabado a láser: sin tinta, solo el relieve hundido.

Sigue de la v8.2:

- **Las otras apps de AVHUB, a mano.** En la columna de pasos, debajo de «Show», aparecen en teclas algo más estrechas que los pasos, más bajas y en un gris más oscuro, con un testigo del color de cada app, los logos de SCREENS, SYSTEMS, NEWS y MSGAME, cada uno enlazado a su web. Van en tinta mate, como grabados en el frontal, y recuperan su color al pasar el cursor. Sustituyen al botón de mediaservi GAME SYSTEM: Al pulsar una tecla se enciende su testigo y, a los tres segundos, se abre esa app. MSGAME se abre desde su tecla, igual que antes. En móvil van en una línea bajo los pasos.

Sigue de la v7.9:

- **VJSHOW estrena logo:** el isotipo de la «sala inmersiva» (tres paredes en perspectiva con las barras del ritmo en la del fondo, que siguen moviéndose) en verde, y el nombre en la letra común de la familia AVHUB, con «vj» en verde. Va en la cabecera y en el icono de la app y de la pestaña.
- MSGAME, que comparte código, estrena también el suyo (el cartucho con dos estrellas, en magenta).

Sigue de la v7.8:

- **Nada cambia en VJSHOW.** Esta versión presenta a Mevi, la mascota que guía al jugador, en la home en 3D de MSGAME (msgame.mediaservi.com): un videoclub dibujado como un cómic de los 80 donde se elige el juego cogiendo su caja de la estantería. VJSHOW y MSGAME comparten el mismo código, por eso las dos webs suben de versión a la vez.

## 🤝 Contribuciones y Feedback

¡El feedback es bienvenido! Si tienes ideas para mejorar la herramienta, has encontrado un bug, o quieres añadir nuevas capas de visualización, siéntete libre de abrir un *Issue* o enviar un *Pull Request* en este repositorio.

## 📄 Licencia

Este proyecto es de código abierto y se distribuye bajo la licencia **GNU GPL v3 (General Public License version 3)**.

Esto significa que eres libre de usar, modificar y distribuir VJSHOW (incluso en eventos comerciales), siempre y cuando cualquier versión modificada que distribuyas mantenga el código abierto bajo esta misma licencia.

---
*VJSHOW v10.2 es un proyecto hecho con ⚙ by [mediaservi.com](https://mediaservi.com)*

## Aviso

Software gratuito y de código abierto, hecho con pasión por un aficionado en su tiempo libre. No es un producto profesional. Se ofrece «tal cual», sin garantías de ningún tipo; los resultados son orientativos y hay que comprobarlos siempre; se usa bajo la responsabilidad de cada cual, hasta donde lo permita la ley aplicable. El aviso completo (es/en/ca) está en la propia app, en el enlace «Aviso legal» que acompaña a la línea de crédito. Licencia GPL-3.0.

Documentos legales del repositorio: [`LEGAL.md`](LEGAL.md) (aviso legal), [`DISCLAIMER.md`](DISCLAIMER.md) (garantías y responsabilidad), [`PRIVACY.md`](PRIVACY.md) (privacidad), [`COOKIES.md`](COOKIES.md) (cookies y almacenamiento local) y [`LICENSE`](LICENSE) (GPL-3.0). Sin publicidad, afiliación ni ingresos de ningún tipo.
