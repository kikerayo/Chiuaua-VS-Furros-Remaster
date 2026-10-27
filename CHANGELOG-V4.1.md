# V4.1 — Menú, música y rendimiento

- Menú principal renovado con halo animado, partículas ligeras, botones compactos y transiciones suaves. Salir queda visible.
- Jugar ofrece Supervivencia y Sandbox; el acceso a Sandbox se mueve dentro de Jugar.
- Catálogo paginado: diez miniaturas por página, generadas de los modelos reales y conservadas en caché. Las escenas 3D temporales se liberan al terminar la captura.
- La vista del personaje se detiene detrás de las ventanas. Menos cálculos de separación entre enemigos y menos actualizaciones del fuego, sin reducir la frecuencia del movimiento ni de los ataques.
- Música del usuario: menu.mp3 en el menú, catalog.mp3 en el catálogo y Ajustes.mp3 en ajustes, con fundido de 0,55 segundos. El menú sube y el catálogo entra desde abajo.
- Toast con el nombre del mapa al entrar a jugar, después de la cinemática. Sonido: primeros 4 segundos del archivo zone proporcionado, con salida suave.
- 28 skins. Homero, Chihuahua 777, Doritos, Brasil 9, Tripulante rojo y Mango eléctrico se añaden al final del catálogo.
- Las 28 skins y el furro usan mallas refinadas en Blender. Se mantienen los diseños, con bordes redondeados y contornos suaves. Homero tiene camisa sin intersecciones, pantalón redondeado y capa continua con nubes.
- Sandbox de PC: biblioteca de 56 elementos; colocar, seleccionar, mover, girar, escalar, duplicar, borrar, deshacer y rehacer. Base vacía o una de las 12 plantillas. Hasta 250 objetos por escena.
- Tres ranuras de guardado e importación/exportación JSON de escenas con animaciones y voz.
- Línea de tiempo con claves de objetos y cámara, interpolación suave, bucle y películas de 1 a 120 segundos. Acciones de personajes: quieto, caminar, saltar y ladrar.
- Edge TTS para Windows: cuatro voces en español y diálogo sincronizado. Requiere Internet; el texto se envía al servicio de voz de Microsoft. La herramienta va incluida.
- Dos bosses exclusivos de Sandbox: gato inspirado en la foto original, con embestidas y 400 de vida; robot trípode, con láseres y 650 de vida.
- En móvil se bloquea la creación y edición de escenas, animaciones y voces. Se pueden jugar tres escenas preparadas e importar escenas de PC para jugar o ver su animación.
- Se mantienen MikaFurro cada 10 rondas, TITAN CHIHUAHUA MAN más alto, mapas infinitos, drops y controles móviles.

Validación: pruebas automáticas y revisión visual silenciosa; generación real con Edge TTS. APK firmado y alineado a 16 KB. Falta probar la instalación en un teléfono físico. No se escuchó audio durante las pruebas.
Multijugador sigue pospuesto. YouTube en Android sigue pendiente del servicio de música.

