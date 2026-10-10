---
estado: bloqueado
siguiente_paso: Cuando la release v1.4.0 esté publicada con los tres paquetes, actualizar los enlaces de descarga de la web (Windows, Mac y Linux).
bloqueo: "Nilo: crear la release v1.4.0 en GitHub (instalador, .dmg y .deb) y subir el .appx a Partner Center."
actualizado: 2026-10-10
---

# Estado

La v1.4.0 (hito 10, el último de funciones) está etiquetada: builds de Windows (instalador NSIS y MSIX para la Store), Mac (`.dmg` universal con firma ad hoc, probado por Nilo en un MacBook con Apple silicon y un monitor externo) y Linux (`.deb` para Debian y Ubuntu, probado en Linux Mint 22.3 y Ubuntu 24.04 con X11), y siete idiomas nuevos (catalán, alemán, francés, italiano, neerlandés, portugués y andaluz EPA, este solo a mano). Riesgo conocido: Linux con Wayland y XWayland en equipos reales, sin probar.

A partir de aquí, promoción y mantenimiento; no hay más hitos de funciones previstos.

## Diario

- 2026-10-10: el .dmg funciona a la primera en un MacBook con Apple silicon y monitor externo. feat/mac y feat/linux fusionadas en main, idiomas nuevos registrados, v1.4.0 etiquetada; esperando a que Nilo publique la release.

- 2026-10-09: sesión cerrada; en pausa hasta que Nilo pueda probar el .dmg en un Mac.
- 2026-10-09: el .deb funciona en Ubuntu 24.04 desde USB en un portátil real (sesión X11); Nilo da por terminadas las pruebas de Linux.
- 2026-10-09: el .deb pasa todas las pruebas en Linux Mint 22.3 MATE (portátil real); en Ubuntu 24.04 (VirtualBox, Wayland) no abre la ventana, en estudio.
- 2026-10-09: primer .deb de Linux (rama `feat/linux`), compilado y con la prueba de humo en verde; en manos de Nilo para probarlo.
- 2026-10-09: el andaluz pasa a `es-x-andaluh.json` (etiqueta BCP 47 válida; nunca automático, se elige a mano).
- 2026-10-09: andaluz (Andalûh, EPA) en `locales/es-an.json`, sin registrar; backlog al día.
- 2026-10-09: traducciones fr, de, it, nl, pt (de Portugal) y ca en `locales/`, sin registrar todavía en la app.
- 2026-10-09: la Store aprueba la 1.3.0; vuelve el botón de la Store a la web.
- 2026-10-08: backlog movido de docs/developer-guide.md a guppy/BACKLOG.md y puesto al día.
- 2026-10-08: guppy/STATUS.md creado.
