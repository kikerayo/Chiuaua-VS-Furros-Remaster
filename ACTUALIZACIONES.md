# Canal de actualizaciones

El juego 2V consulta latest.json al arrancar y desde Ajustes > Perfil y actualizaciones. Solo acepta una versión superior a su código actual (2), enlaces del repositorio y SHA-256 válido. La instalación requiere pulsar el botón; Windows conserva un .exe.bak. Android usa el instalador del sistema.

Para publicar la siguiente versión: subir EXE y APK a una Release; obtener sus SHA-256; actualizar version, version_code y los dos objetos de latest.json con las direcciones reales. Incrementar también el código Android y conservar la misma firma. Nunca publicar claves, contraseñas ni el almacén de firma.

La 2V es la primera con este canal. Las copias antiguas 1V deben actualizarse manualmente una vez. El multijugador está pospuesto. Extracción YouTube disponible en Windows; Android requiere un servicio pendiente.
