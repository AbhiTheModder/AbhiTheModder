

# Abhi / AbhiTheModder

<img src="https://gitfut.com/AbhiTheModder.png" alt="Tarjeta de perfil de GitFut para AbhiTheModder" width="120" align="right" />

Investigador en **seguridad móvil** e ingeniero inverso especializado en internals de Android, seguridad de aplicaciones, Dalvik/Smali, Flutter/Dart, instrumentación con Frida/Pine, radare2 y herramientas priorizadas para Termux.

Desarrollo herramientas basándome en los problemas que encuentro al hacer ingeniería inversa: exploración de DEX y Smali, hooking en tiempo de ejecución, análisis de APK, YARA nativo para Android, flujos de trabajo con radare2 y automatización para tareas repetibles de seguridad móvil.

**Ocasionalmente exploro la seguridad web.**

## Enfoque de investigación

- Evaluaciones de seguridad de aplicaciones Android, ingeniería inversa de APK ofuscados, análisis de comportamiento de malware e inteligencia de amenazas.
- Bytecode Dalvik, Smali, comportamiento del runtime ART, internals de Java/Kotlin en Android, JNI, código nativo y análisis de AOT de Flutter/Dart.
- Análisis dinámico e instrumentación con Frida, PineHook, radare2, agentes personalizados y flujos de trabajo nativos de Android/Termux.
- Herramientas de ingeniería inversa, automatización de seguridad y pipelines de análisis asistidos por IA/MCP.

## Investigación pública

- [CVE-2026-33989](https://www.cve.org/CVERecord?id=CVE-2026-33989): escritura de archivos arbitrarios mediante path traversal en `@mobilenext/mobile-mcp`, corregido en `0.0.49` y publicado a través de [GHSA-3p2m-h2v6-g9mx](https://github.com/mobile-next/mobile-mcp/security/advisories/GHSA-3p2m-h2v6-g9mx).
- [Análisis de CVE-2026-33989](https://qbtau.in/posts/cve-2026-33989/): análisis técnico del manejo de rutas en `mobile_save_screenshot` y `mobile_start_screen_recording` en un servidor MCP móvil.
- [Charla en r2con2025](https://github.com/radareorg/r2con2025/tree/main/r2web): Acceder a r2 desde cualquier lugar y en cualquier momento.
- [Notas de investigación y análisis](https://qbtau.in/posts/): ingeniería inversa de Android, análisis de SSL en Flutter, internals de Dart AOT, Frida en Termux, parcheo de Smali, emparejamiento de firmas y análisis de CTFs.

## Trabajos seleccionados

### RevEngi

- [RevEngiBot](https://t.me/RevEngiBot): toolkit de ingeniería inversa basado en Telegram.
- [revengi-app](https://github.com/RevEngiSquad/revengi-app): aplicación Flutter para gramática Smali, DexRepair, análisis de Flutter, integración con Blutter, herramientas APK y flujos de trabajo relacionados.
- [Documentación de RevEngi](https://github.com/RevEngiSquad/docs): documentación para el bot, API y aplicación.
- [yarax_android](https://github.com/RevEngiSquad/yarax_android): bindings nativos JNI de Android para `yara-x`.

### Android, Smali y DEX

- [understand-smali](https://github.com/AbhiTheModder/understand-smali): material de aprendizaje y referencia para Smali y bytecode de Android.
- [smalisp](https://github.com/AbhiTheModder/smalisp): servidor de lenguaje Smali ligero con definiciones y autocompletado.
- [smalig](https://github.com/RevEngiSquad/smalig): herramienta de obtención de información y gramática de bytecode Dalvik/Smali.
- [java2smali](https://github.com/RevEngiSquad/java2smali): herramienta de línea de comandos para compilar Java a Smali.
- [MT-NotepadPlus](https://github.com/AbhiTheModder/MT-NotepadPlus): resaltado de sintaxis Smali para Notepad++.

### Instrumentación en tiempo de ejecución

- [PineHookPlus](https://github.com/RevEngiSquad/PineHookPlus): asistente basado en PineHook para hacer hook de clases y métodos con menos código repetitivo.
- [Fine](https://github.com/AbhiTheModder/Fine): experimentos de integración de Pine y Frida sobre el comportamiento de la fábrica de componentes de Android.
- [NewPineExample](https://github.com/AbhiTheModder/NewPineExample): prueba de concepto de hook Pine que utiliza el atributo de manifiesto `android:name` de Android.
- [frida-python](https://github.com/AbhiTheModder/frida-python): variante de los bindings de Python de Frida con soporte para devkit.
- [frida-agent-api](https://github.com/AbhiTheModder/frida-agent-api): compilador ligero de agentes Frida y API.

### Análisis binario y radare2

- [r2web](https://github.com/radareorg/r2web): interfaz web para acceder a radare2 desde cualquier lugar.
- [warrp](https://github.com/radareorg/warrp): plugin nativo de radare2 para firmas WARP de Binary Ninja.
- [nyxstone-r2](https://github.com/AbhiTheModder/nyxstone-r2): plugin de ensamblador nyxstone para radare2.
- [r2garlic](https://github.com/radareorg/r2garlic): trabajo de descompilación Android/DEX alrededor de radare2.

### Termux, Automatización y APIs

- [termux-scripts](https://github.com/AbhiTheModder/termux-scripts): scripts para instalar y utilizar herramientas de ingeniería inversa en Android/Termux.
- [termux-hermes](https://github.com/AbhiTheModder/termux-hermes): notas de compilación y lanzamientos de Hermes en Termux.
- [blutter-termux](https://github.com/dedshit/blutter-termux): flujo de trabajo B(l)utter orientado a Termux mantenido con mejoras.
- [dex2c](https://github.com/codehasan/dex2c): compilador mantenido de bytecode Dalvik basado en métodos a código nativo JNI.
- [apksearch](https://github.com/AbhiTheModder/apksearch): motor de búsqueda de APK.
- [playstoreapi](https://github.com/AbhiTheModder/playstoreapi): wrapper no oficial de la API de Google Play Store en Python.
- [pyxamstore](https://github.com/AbhiTheModder/pyxamstore): desempaquetar y reempaquetar blobs de ensamblaje de almacén Xamarin, incluidos los formatos V2 y V3.
- [LYADI](https://github.com/AbhiTheModder/LYADI): servidor MCP para asistencia en ingeniería inversa, con enfoque en Android/Termux.

## Escritura

Mi blog es [qbtau.in](https://qbtau.in), donde publico notas técnicas sobre ingeniería inversa de Android, internals de Flutter/Dart, Frida, Smali, herramientas móviles, CVEs y CTFs.

Temas recientes incluyen:

- Compilar Frida nativamente en Android/Termux.
- Emparejar clases y métodos Java entre versiones de APK.
- Identificar `ssl_verify_peer_cert` en binarios Flutter de Android.
- Anular los valores predeterminados de los parámetros del constructor de Android en tiempo de ejecución.
- Comportamiento del pool de objetos Dart en ARM64 y ARM32.


## Enlaces

| Plataforma       | Enlace                                                                                                                           |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Correo         | [abhi@revengi.in](mailto:abhi@revengi.in)                                                                                      |
| Sitio web / Blog | [qbtau.in](https://qbtau.in)                                                                                                   |
| GitHub         | [github.com/AbhiTheModder](https://github.com/AbhiTheModder)                                                                   |
| RevEngi        | [github.com/RevEngiSquad](https://github.com/RevEngiSquad), [revengi.in](https://revengi.in)                                   |
| Telegram       | [@AbhiTheM0dder](https://t.me/AbhiTheM0dder), [Chat RevEngi](https://t.me/RevEngiSquad), [RevEngiBot](https://t.me/RevEngiBot) |
| Mastodon       | [@AbhiTheModder@defcon.social](https://defcon.social/@AbhiTheModder)                                                           |
| Bluesky        | [@qbtau.in](https://bsky.app/profile/qbtau.in)                                                                                 |
| X              | [@AbhiTheModder](https://x.com/AbhiTheModder), [@Qbtaumai](https://x.com/Qbtaumai)                                             |
| LinkedIn       | [linkedin.com/in/abhisom](https://www.linkedin.com/in/abhisom/)                                                                |
| GitLab         | [gitlab.com/AbhiTheModder](https://gitlab.com/AbhiTheModder)                                                                   |
| YouTube        | [@AbhiTheModder](https://www.youtube.com/@AbhiTheModder)                                                                       |

<details>
<summary><b>Estadísticas e insignias de GitHub</b></summary>

[![Una imagen de las insignias Holopin de @abhithemodder, que es un enlace para ver su perfil completo de Holopin](https://holopin.me/abhithemodder)](https://holopin.io/@abhithemodder)

| Estadísticas | Racha | Idiomas principales |
| --- | --- | --- |
| [![Estadísticas de AbhiTheModder](https://github-stats-extended.vercel.app/api?username=AbhiTheModder&show_icons=true&theme=transparent&hide_border=true)](https://github.com/stats-organization/github-stats-extended) | [![Racha de GitHub](https://streak-stats.demolab.com?user=AbhiTheModder&theme=dracula&currStreakLabel=437C85&sideLabels=437C85&ring=007BEB&fire=007BEB&sideNums=007BEB&background=FFFFFF00&dates=437C85&hide_border=true)](https://git.io/streak-stats) | [![Idiomas principales de AbhiTheModder](https://github-stats-extended.vercel.app/api/top-langs/?username=AbhiTheModder&show_icons=true&theme=transparent&hide_border=true&layout=compact)](https://github.com/stats-organization/github-readme-stats) |

[![trofeo](https://trophy.benkou.dev/?username=AbhiTheModder&no-bg=true&no-frame=true)](https://github.com/ryo-ma/github-profile-trophy)

<img src="https://github.com/AbhiTheModder/AbhiTheModder/blob/main/github-metrics.svg" alt="Métricas detalladas de contribuciones de GitHub" width="100%">

</details>
