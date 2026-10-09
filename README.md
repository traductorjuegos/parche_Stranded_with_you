# Parche para traducir al castellano Stranded With You

Este manual detalla paso a paso para parchear el juego Stranded With You e incluir idioma castellano.

---

## Tabla de Contenidos
1. [Requisitos Previos](#1-requisitos-previos)
2. [Parcheo](#2-parcheo)
3. [Solución de Problemas Frecuentes](#3-solución-de-problemas-frecuentes)

---

## 1. Requisitos Previos

1. **parcheador_multiengine**: Descárgalo [aquí](https://github.com/traductorjuegos/parcheador_juegos_unreal_engine5). (v0.2 o posterior)
2. **parche_traduccion_stranded_with_you_español.zip**: Incluído en este mismo repo.
---

## 2. Parcheo

1. Ejecuta parcheador_multiengine
2. En Paquete de traducción, selecciona el parche **parche_traduccion_stranded_with_you_español.zip**
3. En Carpeta del juego, selecciona la carpeta donde se encuentra el fichero ejecutable del juego (Game.exe)
4. Marca:
	- Crear copia de seguridad
5. Pulsa en PARCHEAR.
6. Tras parchear con éxito, pulsa JUGAR.

## 3. Solución de Problemas Frecuentes

### Quiero quitar el parche del juego y dejarlo como estaba antes.
* Si pulsaste la opción _Crear copia de seguridad_ cuando aplicaste el parche, abre el parcheador, realiza los puntos 2 y 3 del paso anterior y pulsa en **Restaurar Original**.

### No restaura bien el original cuando pulso en _*Restaurar Original*_
* Accede a la carpeta de instalación del juego y luego busca el directorio data/backup_original. Todos los ficheros json (excepto installed_assets.json) los debes copiar en el directorio data/. Todos los ficheros dentro del directorio assets debes copiarlos en el directorio del juego (donde se encuentra Game.exe).
