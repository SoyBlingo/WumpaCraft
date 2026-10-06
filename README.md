# WumpaCraft
Por SoyBlingo. Crash Bandicoot en Minecraft Java 1.21.4 (Fabric). Solo un jugador.

## Descarga 0.3.0
El paquete instalable está en [Releases](https://github.com/SoyBlingo/WumpaCraft/releases).
Descarga `WumpaCraft-0.3.0.zip`; el JAR por sí solo no contiene los recursos necesarios.
`melty.recipe.json` describe la instalación y la preparación de los recursos locales.
La instalación a través de Melty todavía está pendiente de prueba.
El código del mod y del preparador está en `WumpaCraft-0.3.0-source.zip`.
Para compilar el mod: Java 21, Gradle 8.14.3 y Python 3; ejecutar `gradle build` en `crash-mod`.
Las herramientas que usa el preparador se describen en `Setup/tools.json`.

## Jugar desde Melty
Requiere Minecraft Java y una copia instalada de Crash Bandicoot N. Sane Trilogy para PC.
Melty prepara una instancia separada de Minecraft y los recursos desde tu copia local de Crash.
Prism Launcher puede pedir iniciar sesión con tu cuenta de Microsoft que posee Minecraft.
La primera preparación tarda varios minutos y necesita espacio libre; las siguientes usan la caché.
No es necesario abrir Crash. No se incluyen modelos, texturas, sonidos ni animaciones del juego.

## Controles
Espacio: salto/doble salto. R: giro. C: deslizar. Z: bazooka.
Clic derecho: apuntar con zoom; izquierdo: disparar (5 Wumpas).
Con la bazooka guardada, clic derecho come Wumpas: 1 corazón y 1 muslo.
V: activar invencibilidad con 3 máscaras. F5: cámara. F6: activar/desactivar Crash.
El libro del inventario explica los controles y las reglas de Aku Aku.

## Compatibilidad y diagnóstico
Windows x64, Minecraft 1.21.4 y Fabric API incluidos en la configuración de Prism.
Modo individual exclusivamente. No habilitar LAN ni servidores para estas habilidades.
Setup/prepare.log muestra la preparación; Prism/instances/WumpaCraft/.minecraft/logs/latest.log muestra el juego.
Desinstalar desde Melty. Conserva una copia de tus mundos antes de borrar la instancia.

## Créditos
Avisos de componentes reutilizados en `THIRD-PARTY.txt` y en sus carpetas de licencias.
Idea, dirección y pruebas: SoyBlingo. Programación y preparación asistidas por Codex (OpenAI).
Conversor PAK basado en la investigación de Kishimisu/The Apprentice (MIT).
Prism Launcher 11.1.1, GPL-3.0: https://github.com/PrismLauncher/PrismLauncher/tree/11.1.1
Fabric API, Apache-2.0: https://github.com/FabricMC/fabric
Python, NumPy, Pillow, SoundFile, py7zr y dependencias conservan sus licencias en Setup/runtime.
HavokToolset (GPL-3.0) y vgmstream se descargan de sus releases oficiales durante la preparación;
sus licencias acompañan dichas herramientas. No se redistribuyen sus binarios en este paquete.
https://github.com/PredatorCZ/HavokLib — https://github.com/vgmstream/vgmstream
Crash y sus recursos pertenecen a sus titulares. Proyecto de fans no oficial.

VIVA CHILE Y LOS PIPIPUPIS
