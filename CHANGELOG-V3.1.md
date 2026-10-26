# Chiuaua VS Furros Remaster · V3.1

- Catálogo de 19 skins con tarjetas 3D, vista previa e indicador de aspecto equipado.
- Menú renovado: colores, entradas suaves, movimiento sutil del personaje y respuesta al pasar por los botones.
- Animación de caminar y detenerse más suave, inclinación del cuerpo y postura de dash.
- El drop equipado gira sobre su nombre. Funciona en tercera persona, primera persona y móvil; desaparece al quedarse sin cargas.
- Con Gucci Chihuahua, la pistola equipada, su vista del inventario, los portales y el disparo son amarillos. Con los otros aspectos siguen verdes.
- Sonido de portal suministrado por el usuario; variantes distorsionadas del láser Roblox para Skibidi, uranio y rayos rojos; fire-burning para el bocadillo picante. El fuego se detiene al agotarse el efecto.
- Sonidos grabados para interfaz, pasos, ladrido, daño, curación y eventos. Se sustituyen los pitidos sintetizados anteriores. Recursos incluidos, sin descargas durante la partida.
- Los once episodios originales del 6 al 16 se incluyen como cinemáticas completas y se asignan a sus mapas. El 17 conserva su intro recortada. Ciudad en llamas entra sin cinemática.
- Skip aparece cuando los nueve sectores del mapa están listos. La partida permanece detenida hasta pulsarlo; puedes seguir viendo la historia antes de entrar.
- La interfaz muestra títulos del juego: sin nombres de archivo, tiempos de referencia ni etiquetas de desarrollo.
- El origen de los mapas se conserva en NOTAS-LORE.md y assets/story/SOURCES.json, separado de la interfaz. El material original de los vídeos se conserva; no se han inventado diálogos ni se han eliminado sus marcas.

## Comprobaciones

La revisión del ejecutable comprende 261 comprobaciones de lógica: combate, exploración, controles móviles simulados, carga, catálogo, vistas de drops, cinemáticas y sonidos. Las tres comprobaciones que dependen de captura nativa del ratón se omiten en modo sin ventana. Se verificó además el catálogo con un clic de ratón simulado en renderizado OpenGL real y se revisaron capturas del menú, catálogo, carga y HUD.

Los 30 archivos de vídeo y efectos incluidos se decodificaron sin errores. Las duraciones de los once episodios convertidos se contrastaron con los originales. La escucha humana no se realizó: las comprobaciones permanecieron silenciadas.

El APK mantiene el mismo paquete y firma, con código de versión 4. Se comprueban firma, alineación y contenido; instalación y rendimiento en un teléfono real pendientes.

Multijugador y extracción YouTube en Android siguen pospuestos. V3.1 publicada para Windows y Android, con canal de actualizaciones activado.

## Procedencia de sonidos

- Archivos de portal, láser y fuego suministrados por el usuario; originales incluidos en assets/sfx/originals.
- [Explorador de sonidos de Minecraft de Lodestone](https://lode.gg/tools/minecraft-sounds). Muestras de Minecraft 1.21.1 descargadas del servidor oficial de recursos de Mojang; identificación y hashes en assets/sfx/SOURCES.json.
- Myinstants: [Vine Boom](https://www.myinstants.com/en/instant/vine-boom-sound-70972/) para derrota y [Ding](https://www.myinstants.com/en/instant/ding-sound-effect/) para equipar. Direcciones en assets/sfx/MYINSTANTS-SOURCES.json.

