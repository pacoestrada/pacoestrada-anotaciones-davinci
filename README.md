# Anotaciones para DaVinci · Paco Estrada

Colección de 30 plantillas de Fusion para señalar un botón, destacar una fila, numerar pasos u ocultar datos al editar un tutorial. Incluye 27 títulos y tres efectos. Puedes cambiar la posición y el tamaño desde el Inspector de la página Edición.

**[Descargar el instalador 1.1.0 (.drfx)](./Anotaciones_DaVinci_Paco_Estrada_1.1.0.drfx)** · [Notas de la versión](./RELEASE.md) · [Licencia MIT](./LICENSE)

Si el enlace abre la ficha del archivo, pulsa el botón de descarga. La distribución incluye también las plantillas editables en [Edit](./Edit).

## Instalación

1. Descarga el archivo con extensión `.drfx`.
2. Ábrelo con DaVinci Resolve y acepta la instalación. También puedes arrastrarlo desde el explorador de archivos a la página Fusion.
3. En **Edición → Efectos**, abre **Títulos** y busca la categoría **Paco Estrada - Anotaciones**. Los tres desenfoques aparecen en **Efectos**. Si el listado sigue igual, reinicia Resolve.

La colección usa nodos estándar de Fusion. Los títulos con texto usan DejaVu Sans. Si hace falta, puedes elegir otra fuente desde el Inspector. Paco probó la versión base en DaVinci Resolve Studio 21 sobre Linux Mint. La comprobación de los 30 recursos para esta publicación incluye la integridad del paquete y la identidad con el instalador 0.2. La prueba individual de cada recurso en Windows, macOS y Resolve Free queda pendiente.

## Primer uso

- Para señalar un control, arrastra **01 Flecha recta** a V2, encima de la captura de V1. Sitúa el cabezal dentro del título, selecciónalo y ajusta posición, escala, ángulo y grosor. Ajusta su duración arrastrando el extremo del título. Usa **Entrada = 0** si lo quieres visible desde el primer fotograma.
- Para tapar una dirección, coloca **24 Tapa negra** encima de la captura. Ajusta ancho y alto con margen alrededor del dato y alarga la tapa mientras siga visible. Para una captura con desplazamiento, anima la posición y revisa los fotogramas exportados, incluidos el primero y el último.
- Para desenfocar una zona, arrastra **27 Desenfoque rectangular** al propio clip de vídeo. En el Inspector ajusta la posición, el tamaño y la intensidad. Para datos sensibles, elige una tapa opaca.
- Para destacar una zona conservando el detalle central, usa **29 Desenfoque exterior** sobre el clip o **30 Foco de atención** en la pista superior.

## Actualización y desinstalación

La 1.1.0 contiene las mismas plantillas que la 0.2. Si actualizas, cierra Resolve y mueve el archivo `Anotaciones_DaVinci_Paco_Estrada_0.2.drfx` fuera de la carpeta de plantillas antes de instalar la nueva versión. Si tienes la 0.1, retira también su archivo. En Linux Mint la ruta de usuario es `~/.local/share/DaVinciResolve/Fusion/Templates/`.

Para desinstalar la 1.1.0, cierra Resolve, retira únicamente `Anotaciones_DaVinci_Paco_Estrada_1.1.0.drfx` de esa carpeta y vuelve a abrir la aplicación.

## Catálogo

| Recurso | Dónde se aplica |
| --- | --- |
| 01 Flecha recta | Título en pista superior |
| 02 Flecha doble | Título en pista superior |
| 03 Flecha arqueada | Título en pista superior |
| 04 Flecha en codo | Título en pista superior |
| 05 Flecha maciza | Título en pista superior |
| 06 Flecha trazo libre | Título en pista superior |
| 07 Subrayado | Título en pista superior |
| 08 Subrayado doble | Título en pista superior |
| 09 Subrayado ondulado | Título en pista superior |
| 10 Rotulador verde | Título en pista superior |
| 11 Rotulador amarillo | Título en pista superior |
| 12 Marco rectangular | Título en pista superior |
| 13 Marco redondeado | Título en pista superior |
| 14 Marco ovalado | Título en pista superior |
| 15 Marco de esquinas | Título en pista superior |
| 16 Circulo | Título en pista superior |
| 17 Anillo pulsante | Título en pista superior |
| 18 Punto pulsante | Título en pista superior |
| 19 Clic doble anillo | Título en pista superior |
| 20 Paso numerado | Título en pista superior |
| 21 Etiqueta | Título en pista superior |
| 22 Llamada con linea | Título en pista superior |
| 23 Marca de verificacion | Título en pista superior |
| 24 Tapa negra | Título en pista superior |
| 25 Tapa neutra | Título en pista superior |
| 26 Tapa con texto | Título en pista superior |
| 27 Desenfoque rectangular | Efecto sobre el clip |
| 28 Desenfoque ovalado | Efecto sobre el clip |
| 29 Desenfoque exterior | Efecto sobre el clip |
| 30 Foco de atencion | Título en pista superior |

## Archivos editables

Las carpetas `Edit/Titles` y `Edit/Effects` contienen los originales en formato `.setting`. Para reconstruir el instalador en Linux, ejecuta desde la raíz del proyecto:

```bash
zip -qr Anotaciones_personalizadas.drfx Edit
```

Puedes verificar el instalador descargado con `sha256sum -c SHA256SUMS` desde su carpeta. © 2026 Paco Estrada.
