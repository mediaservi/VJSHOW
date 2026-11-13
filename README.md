# 🪩 VJSHOW - Generador de Visualizaciones Reactivas

Creada con pasión por **Mediaservi** para la comunidad de VJs, llega VJSHOW. Una herramienta simple, pero increíblemente potente, diseñada para que logres resultados espectaculares y ese "efecto wow" con total facilidad.

Visualiza la música y déjate envolver por un espectáculo de capas reactivas en tiempo real. Úsala desde tu navegador, Smart TV o descárgatela en tu ordenador. Amplifica tus fiestas, eventos y que empiece el VJSHOW. Por fin visuales increíbles que se generan fácil junto con opciones de control y ajuste fino.

🔗 **Pruébala en vivo ahora mismo:**
- **[vjshow.mediaservi.com](https://vjshow.mediaservi.com)**

**Versión actual: v12.0**

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

## 🆕 Cambios de la versión actual (v12.0)

- **VJSHOW y MSGAME son ya dos apps independientes.** Cada una tiene su código fuente en su repositorio y su propia numeración; el `index.html` de MSGAME deja de generarse a partir de este.
- **Los juegos viven solo en MSGAME.** De este repositorio salen las carpetas `juegos/`, `borradores/` y `packs/`, y la música de los juegos (`sonidos/ingame_*` y `menu_gamesystem`): la descarga pasa de unos 46 MB a unos 8,5 MB. Del código salen el videoclub en 3D (la home de MSGAME) y la página del móvil como mando.
- Los enlaces de mando, de reto y de cartucho (`?pad=`, `?reto=`, `?juego=`) que lleguen a VJSHOW se abren en MSGAME, igual que el botón «mediaservi GAME SYSTEM» del rack.
- En VJSHOW no cambia nada a la vista: los cuatro pasos, la sala inmersiva, las capas, el modo feria y la copia sin conexión siguen igual.
- **Pendiente (segunda fase):** el motor de los juegos sigue dentro de `index.html`, sin uso, porque comparte con VJSHOW los sonidos de la interfaz y sus ajustes. Se retirará cuando ese módulo de sonido esté separado.

### v11.8 (última versión con el código compartido con MSGAME)

- **KRAZYGOLF · modo KRAZY en 3D**, a la altura del clásico: cada hoyo es un rincón de casa modelado entero. La encimera (mantel de cuadros, terrones de azúcar, tostadora con sus tostadas, harina derramada, taza, aceitera, frutero, salero), el despacho (vade, libros, teclado con teclas, ventilador de sobremesa que gira, monitor, flexo, lápices) y el salón (alfombra con flecos, piezas de construcción, puf, robot aspirador, sofá, lámpara y planta). Las pelotas absurdas también son 3D: huevo, cubito de hielo translúcido, albóndiga, saltarina que bota y pelota de playa.
- **KRAZYGOLF · modo nuevo SIMULATOR**: simulador de golf como los de sala, visto desde detrás de la bola. Campo propio e inventado, **AVHUB Golf Links & Park**, de 9 hoyos con trazado de ida y vuelta: sale de la casa club por el parque (arbolado, lagos, un río con puente), llega a la costa (dunas, búnkeres de olla, hierba alta, viento, faro y mar) y vuelve a la casa club. Recorrido corto de 3 hoyos o completo de 9 (par 36).
  - Terreno con relieve, calles segadas a franjas, greens, antegreens, rough, arena y agua; cada suelo frena y penaliza distinto. Nueve palos (del driver al putter) con recomendación automática, viento, efecto, bote y rodadura, agua y fuera de límites con penalización, putt dado a menos de un metro.
  - Pantalla de simulador: panel de datos (distancia al hoyo, palo, alcance, lie, viento), plano del hoyo, marca de caída, traza del vuelo y datos del golpe (vuelo, total, velocidad de bola, altura, desvío).
  - **Logo de AVHUB** en la casa club, las banderas, las vallas de detrás de cada green, el cartel de cada salida, la caseta y el faro.
- **WONDERWALK en 3D**: el paseo ya no es un dibujo plano. Sendero con relieve, árboles, flores, farolas, río con puente de madera y castillo; luz que pasa del atardecer a la noche con estrellas, luna y la punta de la varita iluminando; bosque con niebla; sombras. Piedras, arbustos, troncos, zarzas, ladrones y caminantes son modelos 3D. La lista, la mochila y las fichas siguen encima, más grandes en móvil vertical.
- **Funciones de móvil en los dos juegos**: ya son juegos de MSGAME como los demás (turnos, marcador final y récords).
  - WONDERWALK: el móvil es la varita; se apunta y se pulsa «Tocar».
  - KRAZYGOLF (KRAZY y CLÁSICO): se mantiene el botón, se apunta hacia donde se quiere tirar (más lejos, más fuerte) y se suelta.
  - SIMULATOR: el móvil es el palo. Se apunta, se mantiene el botón, se balancea y se suelta; el giro de muñeca da efecto y ◀ ▶ cambian de palo. Sin móvil: mantener pulsado y soltar en la marca, o deslizar hacia arriba.
- Dejan de llevar el rótulo de «borrador».

### v11.7

- **Continuidad del equipo**: el menú del juego ya no usa una tele, una consola y un cartucho dibujados. Se muestra sobre **los mismos de la sala 3D** (la cámara solo se acerca), con la lámpara de lava, la caja del juego en la mesa y el cartucho metido en la consola. En móvil se ve la tele en primer plano para que la letra no quede pequeña.
- **Menú nuevo dentro de la pantalla**: la carátula original a la izquierda; a la derecha el logo de MSGAME y las opciones en lista; y al pie **dos filas fijas de botones de servicio**: JUGAR, EXPULSAR, RESTABLECER, VOLVER / JUGADORES, RÉCORDS, MÚSICA, SONIDOS (los dos últimos con piloto de encendido).
- **La caja se abre en primer plano**: Mevi la sostiene delante, centrada y de frente, con una mano a cada lado, simétricas; la abre como un libro y saca el cartucho. Manos, caja y cartucho se pintan en una capa por delante de la sala, así que los brazos no pueden mezclarse con la tele ni con nada de la mesa. El cartucho se mete en la consola en un plano de frente.
- **La caja queda en la mesa de una forma distinta cada vez** (cerrada, entreabierta, de par en par, de lado…), siempre en el hueco libre.
- **Al expulsar, el cartucho y la caja se evaporan en píxeles** con los colores de su carátula, de arriba abajo.
- **SHATEKI con premios de verdad**, como LA FORTUNA: en la ficha del juego se escriben los premios y cuántos hay de cada uno (0 = sin límite); cada unidad sale en las gradas como una **caja dorada con lazo** y quien la tira del estante se la lleva (se descuenta de las existencias y queda apuntado a su nombre). En pantalla: lista de premios, entregados y QR para unirse con el móvil. Varios jugadores juegan por turnos de 7 corchos.
  - Las cajas de los productos de AVHUB van todas en **gris antracita**; los dulces de colores, las latas y los gatos son relleno.
  - Miras a tamaño real: alza con muesca y punto de mira en cuña del mismo metal.
- Si el aparato va lento y se salta planos de la secuencia, el final es siempre el mismo: cartucho en la ranura y caja en la mesa.
- El logo de MSGAME se pide con una dirección nueva para que nadie siga viendo el antiguo desde la copia guardada.

### v11.6

- **Juego nuevo: SHATEKI · galería de tiro de Osaka**, con su cartucho y su carátula. Caseta de feria japonesa en 3D: gradas rojas llenas de premios (cajas con las marcas de mediaservi, dulces, latas, gatos de la suerte y los tres dorados del altarcillo), rótulos de caligrafía y bombillas.
  - Se dispara con un **rifle de corchos visto por sus miras, sin cruceta**: el alza es una pletina con muesca y el punto de mira se ve dentro. El pulso tiembla un poco y, si el punto de mira se va a un lado de la muesca, el corcho se va hacia ese lado.
  - **7 corchos por ronda. El premio solo cuenta si cae del estante**: las cajas pequeñas vuelcan con un corcho bien dado arriba; las grandes, las latas y los gatos hay que empujarlos a base de impactos hasta el borde. El corcho cae un poco por el camino.
  - Se juega con el **móvil como rifle** (igual que PUNTERÍA), con el ratón, o con el dedo (un toque apunta y otro dispara). `?juego=shateki` lo abre directamente.

### v11.5

- **Dos cartuchos nuevos en la estantería, con su carátula**: **WONDERWALK** (el camino al castillo) y **KRAZYGOLF** (minigolf gamberro). Siguen en desarrollo: se abren a pantalla completa desde su cartucho y se juegan con el dedo o el ratón; aún no usan el móvil como mando. `?juego=wonderwalk` y `?juego=krazygolf` los abren directamente.
- **WONDERWALK**: el camino ya no es recto, serpentea por prado, bosque y colinas con río y puente; los objetos de la lista están escondidos detrás de piedras, arbustos y troncos (hay que tocar el escondite para mirar), hay zarzas que cortan el paso y ladrones que te roban un objeto si no los espantas.
- **KRAZYGOLF**: la línea de apuntado es gruesa, a rayas en movimiento y acaba en punta de flecha hacia donde saldrá la bola; el modo CLÁSICO se juega en un campo de minigolf en 3D con su jardín (pinos, setos, estanque, valla, farolas y molino).

### v11.4

- **La caja del juego, de pie y con dos manos**: una mano la sujeta y la otra abre la carátula como un libro y saca el cartucho. La caja queda de pie en la mesa, entreabierta y con la carátula a la vista, sin tocar el teléfono ni la consola.
- **Logo nuevo a color** en la consola (sala y menú) y en la etiqueta del cartucho, donde antes iba grabado a una tinta y no se reconocía.
- **ZOMBIELAND**: vuelve a sonar su música de siempre (la del paquete nuevo se ha quitado), los gruñidos suenan solo de vez en cuando y el fondo lleva bancos de humo verde y lila a la deriva.

### v11.3

- **Continuidad de marca**: la cabecera del menú de cada juego lleva el mismo rótulo que su carátula (misma letra, mismos colores, título y variante), en grande, en lugar del texto genérico.
- **Borradores de los juegos nuevos** en `borradores/`: WONDERWALK (paseo hasta el castillo con la lista de objetos) y KRAZYGOLF (tres hoyos, modos KRAZY y CLÁSICO, narrador). Se juegan con el ratón o con el dedo; aún no usan el móvil como mando ni están en la consola.
- `?juego=<variante>` abre directamente cualquier cartucho (zombieland, halloween, fortuna, basket…).
- **Continuidad de la sala**: el fondo de la pantalla del cartucho es una foto de la propia sala tomada en ese momento, con la misma mesa y lo que hay encima (casete, mando, lata, teléfono, caja del juego), en lugar de una imagen aparte.
- **La tapa de la caja** queda levantada al abrirla (antes se tumbaba y se metía en la consola y en la tele).
- **Un cartucho, una variante**: al abrir un cartucho la pantalla ya no ofrece las demás variantes del juego, se abra como se abra.
- ZOMBIELAND alterna su música nueva con la de siempre, una partida con cada una.

### v11.1

- **PUNTERÍA · ZOMBIELAND con recursos propios (piloto)**: los emojis dejan paso a personajes dibujados y animados (dos zombis, hombre lobo, esqueleto, murciélago, rata y un pastor alemán al que no hay que disparar); disparos, recarga, gruñidos y muertes grabados, con varias tomas al azar; y banda sonora propia que entra con su introducción, enlaza con el bucle y cierra con un final (o con el tema de récord). Todo en `packs/zombieland/` (2,2 MB), con sus autores en `CREDITOS.md`. Si un archivo falta, el juego usa lo de antes.
- **Enlace directo**: `?juego=zombieland` carga ese cartucho al abrir.

### v11.0

- **Logo definitivo de MSGAME**: la calavera-cartucho magenta de siempre; «MS» dibujada a mano, angulosa y en 3D, con degradado morado y filete verde; y «GAME» con cada letra calada en su ficha magenta con proporción de carátula, inclinada, con filete verde debajo y la «A» y la «E» un poco más altas. La «S» pisa ligeramente la ficha de la «G». Sustituye al anterior en cabecera, sala, monitor, consola, carátulas y móvil.

### v10.9

- **Logo nuevo de MSGAME**: el cartucho-calavera sigue en magenta y la palabra «msgame» pasa a leerse como una sola, con un degradado vertical de magenta (arriba) a azul (abajo). Aplicado en todos los sitios donde sale el logo: cabecera, sala, consola, carátulas y móvil.

### v10.8

- **MSGAME · carátula de LA FORTUNA**: rótulo en rojo terciopelo (canto granate con filete dorado fino) para que las bombillas amarillas contrasten y se vean mejor.

### v10.7

- **MSGAME · carátula de LA FORTUNA**: las bombillas del rótulo, más marcadas y con más brillo amarillo, de feria (casquillo oscuro, resplandor y filamento claro), sin tapar el rojo de la letra.

### v10.6

- Carátulas definitivas de los cartuchos de la sala de MSGAME y continuidad de su consola. En VJSHOW no cambia nada a la vista.

### Sigue de la v10.5

- Esta versión cambia las carátulas de los cartuchos de la sala de MSGAME (títulos, variantes y fondos nuevos). En VJSHOW no cambia nada a la vista.

### Sigue de la v10.4

- **Espadas, sables y bates más finos (PALOTERAPIA).** La hoja sigue al móvil con menos de la mitad de retraso y responde igual en una tele lenta que en un ordenador rápido. Ahora cuenta la velocidad de la hoja y no solo la del puño: un giro de muñeca también corta (antes no cortaba nada). El barrido entre una imagen y la siguiente ya no se salta objetos, y el margen de corte es algo más generoso. Quieto, sigue sin cortar.
- **Sin latigazos al girar la muñeca.** Si el móvil se tumbaba más de 90°, la espada saltaba de golpe al lado contrario; ahora se queda tumbada de ese lado.
- El resto de cambios de esta versión son de la sala de MSGAME (teléfono rojo en la mesa, brazo y moqueta en la secuencia del cartucho); en VJSHOW no cambia nada más.

### Sigue de la v10.3

- **Calibrar el mando, sin pulsar nada.** Se apunta el borde superior del móvil al centro de la pantalla; sale una cuenta atrás de 3 segundos y el mando se calibra solo en cuanto el móvil está quieto. Después, la bola verde sigue al móvil unos segundos para comprobar que ha quedado bien. Antes había que pulsar un botón, y al pulsarlo (y al mirar el móvil para encontrarlo) se movía justo lo que se estaba midiendo; además, durante el calibrado se veía una bola con el ajuste anterior, que despistaba.
- **El calibrado sale solo** cada vez que un móvil se conecta, si no hay una partida en marcha. Durante el juego, ⊙ Centrar corrige el centro al momento.
- **El mando del móvil, en una pantalla fija.** Ya no se desplaza: arriba, el estado; en el centro, solo los botones del momento; abajo, tres páginas (MANDO, JUEGOS y AJUSTES). Cabe en cualquier móvil, de pie o tumbado, y ningún texto se corta.
- **Cruceta con OK.** Sin partida, el móvil es el mando a distancia de la pantalla: las flechas mueven la selección y OK la pulsa (cartuchos, menús, las iniciales del récord). Con partida, solo salen los mandos de ese juego, más Pausa, Centrar y Salir.
- **Teclas con relieve y clic.** Los botones del móvil se hunden al tocarlos y suenan en el propio móvil (se puede quitar en AJUSTES).
- **Corregido:** al calibrar ya no se hereda un eje invertido de un calibrado fino anterior.

### Sigue de la v10.2

- **Botón «Instalar».** En la cabecera, junto al aviso de fallos, hay un botón nuevo para instalar VJSHOW en el dispositivo como una aplicación más: se abre en su propia ventana, con su icono, y funciona sin conexión con lo que ya se haya usado. Es el mismo botón en toda la familia AVHUB. Donde el navegador no ofrece la instalación directa, el botón explica cómo hacerlo a mano («Añadir a pantalla de inicio»).
- **«Guardar todo para usarla sin internet»**, en esa misma ventana: guarda de una vez toda la app (es el «modo feria» de siempre, ahora más a mano). Y desde la primera visita se guarda ya todo lo que se ha cargado.
- La ventana de instalar se maneja también con el teclado y con el mando de la tele (flechas, OK y atrás), sin que se muevan los controles de debajo.
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
*VJSHOW v12.0 es un proyecto hecho con ⚙ by [mediaservi.com](https://mediaservi.com)*

## Aviso

Software gratuito y de código abierto, hecho con pasión por un aficionado en su tiempo libre. No es un producto profesional. Se ofrece «tal cual», sin garantías de ningún tipo; los resultados son orientativos y hay que comprobarlos siempre; se usa bajo la responsabilidad de cada cual, hasta donde lo permita la ley aplicable. El aviso completo (es/en/ca) está en la propia app, en el enlace «Aviso legal» que acompaña a la línea de crédito. Licencia GPL-3.0.

Documentos legales del repositorio: [`LEGAL.md`](LEGAL.md) (aviso legal), [`DISCLAIMER.md`](DISCLAIMER.md) (garantías y responsabilidad), [`PRIVACY.md`](PRIVACY.md) (privacidad), [`COOKIES.md`](COOKIES.md) (cookies y almacenamiento local) y [`LICENSE`](LICENSE) (GPL-3.0). Sin publicidad, afiliación ni ingresos de ningún tipo.
