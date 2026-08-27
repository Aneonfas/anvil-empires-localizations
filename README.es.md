# Anvil Empires en español

[Elegir idioma](README.md) · [Русский](README.ru.md) · [Informar de un problema](https://github.com/Aneonfas/anvil-empires-localizations/issues)

Traducción no oficial de Anvil Empires Pre-Alpha para Windows/Steam, del proyecto **NFG**. Traduce la interfaz, los objetos, las estructuras, la producción, las misiones y los avisos del juego.

## Descargar

**Versión publicada: 0.1.0, beta, exclusivamente para Steam build 24619810.** Información comprobada el 27/08/2026.

**No instales este paquete en el build 24805551 ni en otro build diferente.** La publicación de un paquete ruso para una versión más reciente del juego no confirma la compatibilidad del paquete español. Espera una versión española compatible.

[Descargar español 0.1.0 — ZIP](https://github.com/Aneonfas/anvil-empires-localizations/releases/download/es-v0.1.0/Anvil-Empires-Spanish-v0.1.0-steam-build-24619810.zip) · [Notas y limitaciones de la versión](https://github.com/Aneonfas/anvil-empires-localizations/releases/tag/es-v0.1.0) · [Suma de comprobación del ZIP](https://github.com/Aneonfas/anvil-empires-localizations/releases/download/es-v0.1.0/Anvil-Empires-Spanish-v0.1.0-steam-build-24619810.zip.sha256)

Descarga el archivo `Anvil-Empires-Spanish-v0.1.0-steam-build-24619810.zip`, no los archivos **Source code** que GitHub genera automáticamente. El ZIP contiene `Anvil-Spanish-Full_P.pak` y documentación; no incluye un EXE ni scripts de instalación.

**Aviso sobre la documentación del ZIP 0.1.0:** sus enlaces a `anvil-empires-spanish` están desactualizados. Para instalar el paquete o pedir ayuda, utiliza esta página y el [repositorio común de localizaciones](https://github.com/Aneonfas/anvil-empires-localizations). El paquete sí está publicado; la antigua nota sobre un «artefacto local» no describe su estado actual. La licencia está en `INFO/LICENSE_ES.txt`.

## Antes de instalar

- Necesitas una copia legítima de Anvil Empires Pre-Alpha instalada mediante Steam en Windows. El Steam App ID es `2383950`.
- Comprueba el **Steam build 24619810** siguiendo los pasos de abajo. La versión que muestra el menú del juego no sustituye al Build ID.
- Mantén el idioma del juego en Steam en **English**, aunque quieras jugar en español.
- Cierra por completo el juego antes de instalar, actualizar, cambiar de idioma o desinstalar. Espera a que Steam termine las descargas y actualizaciones del juego.
- Debe quedar activa **una sola localización**. No modifiques, renombres ni borres `Anvil-Windows.pak`, que pertenece al juego, ni archivos de modificaciones que no conozcas.

### Cómo comprobar el Steam build

Solo vas a leer un archivo de texto de Steam. No cambies ni guardes su contenido.

1. En la biblioteca de Steam, haz clic derecho en Anvil Empires y elige **Administrar → Ver archivos locales**.
2. Se abrirá la carpeta del juego. Busca `steamapps` en la barra de dirección del Explorador de archivos: la ruta habitual es `…\steamapps\common\carpeta del juego`. Sube dos niveles, hasta `steamapps`.
3. Busca **`appmanifest_2383950.acf`** y ábrelo con **Abrir con → Bloc de notas**.
4. Busca **`"buildid"`** con **Ctrl+F** y lee el número que aparece a su derecha. Por ejemplo:

   ```text
   "buildid"    "24619810"
   ```

5. Para este paquete, el número debe ser **24619810**. Cierra el Bloc de notas **sin guardar**.

No lo confundas con `appid`, `TargetBuildID` ni con la versión del menú del juego. Si no encuentras el archivo o el número, o Steam sigue actualizando el juego, no instales el paquete todavía. Completa la actualización y vuelve a comprobarlo. Cambiar el número a mano no cambia la versión instalada del juego.

### Cómo seleccionar English

1. En la biblioteca de Steam, haz clic derecho en el juego y abre **Propiedades**.
2. Busca la opción de **Idioma** del juego y selecciona **English / Inglés**. Según la versión de Steam, puede aparecer como una pestaña propia o dentro de **General**.
3. Si Steam descarga archivos, espera a que termine y comprueba de nuevo el Build ID.

No necesitas cambiar el idioma de la aplicación Steam. Si no aparece el selector, no cambies archivos del juego al azar: consulta la [ayuda oficial de Steam sobre idiomas](https://help.steampowered.com/es/faqs/view/4984-C127-121D-B3F2) o [pide ayuda con la traducción](https://github.com/Aneonfas/anvil-empires-localizations/issues).

## Instalación manual

Si Hub ya gestiona tu paquete, utiliza sus opciones; una sustitución manual puede dejar información desactualizada en Hub. Para desactivarlo temporalmente si Hub falla, consulta la [sección de Hub](#nfg-hub).

1. Comprueba el build y English con los pasos anteriores. **Si el build no coincide, detente y espera una versión compatible.**
2. Descarga el ZIP desde el enlace de esta página y extráelo en una carpeta aparte.
3. Cierra Anvil Empires. Abre los archivos locales desde Steam y entra en **`Anvil\Content\Paks`**.
4. Activa la visualización de extensiones de archivo en el Explorador. Si ya existe **`Anvil-Russian-Full_P.pak`** o **`Anvil-Spanish-Full_P.pak`**, desactiva el paquete anterior **antes** de copiar el nuevo: cambia su nombre para que deje de terminar en `.pak`. Por ejemplo, `Anvil-Russian-Full_P.pak` → `Anvil-Russian-Full_P.pak.disabled`.
5. No sobrescribas una copia de seguridad existente. Si ese nombre ya está ocupado, usa otro, por ejemplo `Anvil-Russian-Full_P.pak.backup-2.disabled`. Si tu traducción anterior tiene otro nombre, identifícala con sus instrucciones; no desactives archivos PAK desconocidos.
6. Copia **solo `Anvil-Spanish-Full_P.pak`** desde la carpeta extraída a `Anvil\Content\Paks`. Comprueba que no queda una segunda localización activa. No toques archivos de otras modificaciones.
7. Inicia el juego desde Steam. Comprueba el menú principal y una ventana habitual del juego. Si no aparece la traducción o algo falla, consulta [«Si algo no funciona»](#si-algo-no-funciona).

**No toques `Anvil-Windows.pak`: es un archivo original del juego.** No necesitas sustituirlo, copiar el ZIP completo al juego ni ejecutar programas adicionales.

## Actualizar, cambiar de idioma o volver atrás

### Actualizar o cambiar de idioma

Comprueba primero el Build ID y la compatibilidad del **nuevo** paquete. Después repite la instalación manual: cierra el juego → desactiva la localización anterior → consérvala con un nombre libre → copia la nueva. Si usas Hub, lee sus limitaciones antes de cambiar de idioma.

**RU 1.0.2 corresponde al build 24805551 y ES 0.1.0 al build 24619810.** No son paquetes intercambiables para el mismo build. No ignores un aviso de incompatibilidad para cambiar de idioma; consulta la [página rusa](README.ru.md) o espera una publicación española compatible.

Si una actualización del juego cambia su Build ID, desactiva la traducción hasta que se confirme la compatibilidad de una versión publicada.

### Desactivar o desinstalar

Si instalaste el paquete manualmente, cierra el juego y cambia el nombre de **`Anvil-Spanish-Full_P.pak`** para que termine en `.disabled`, sin sobrescribir ninguna copia. Es reversible y restaura los textos originales si no hay otra localización activa. Si ya no necesitas la traducción, puedes borrar **solo ese archivo de traducción**; deja intactos los demás archivos del juego.

Si instalaste el paquete con Hub, desinstálalo normalmente desde Hub. Renombrar el PAK desactiva la traducción, pero **no elimina su registro de Hub**.

### Volver a una copia guardada

1. Comprueba que la copia guardada sea compatible con el Steam build **actual**. Una traducción antigua no restaura una versión antigua del juego.
2. Cierra el juego. Desactiva el PAK de la localización actual y consérvalo con otro nombre libre que termine en `.disabled`.
3. Devuelve a la copia elegida su nombre original, por ejemplo `Anvil-Spanish-Full_P.pak`. Comprueba que solo queda una localización activa e inicia el juego.

Si no tienes una copia compatible, deja la traducción desactivada. Puedes consultar los paquetes publicados en [Releases](https://github.com/Aneonfas/anvil-empires-localizations/releases).

## NFG Hub

[Notas de NFG Hub 0.3.0](https://github.com/Aneonfas/nfg-hub/releases/tag/v0.3.0) · [Descargar Hub para Windows x64 — ZIP](https://github.com/Aneonfas/nfg-hub/releases/download/v0.3.0/NFG-Hub-v0.3.0-win-x64.zip)

Hub reúne las localizaciones de Anvil Empires en una misma ficha y permite elegir idioma. Comprueba igualmente el build del juego y el del paquete elegido. Si son diferentes, **no continúes con la instalación**.

**Limitaciones conocidas de Hub 0.3.0 publicado, comprobadas el 27/08/2026:**

- Al pasar de una traducción rusa antigua instalada manualmente al español, Hub puede dejar activo el PAK ruso y no mostrar un conflicto. Antes de cambiar de idioma, cierra el juego y desactiva tú mismo el PAK de la localización anterior siguiendo los pasos de arriba. Solo cambies a un paquete compatible con tu build.
- La desinstalación puede necesitar conexión y fallar sin ella. Para volver temporalmente a los textos originales, cierra el juego y renombra **solo el PAK de la localización instalada** para que termine en `.disabled`, sin sobrescribir copias. Cuando recuperes la conexión, completa la desinstalación en Hub. Su registro puede seguir apareciendo hasta entonces; no borres a mano las bases de datos ni los archivos internos de Hub.

La corrección de estas limitaciones todavía no está publicada. Revisa las [versiones de Hub](https://github.com/Aneonfas/nfg-hub/releases) antes de actualizar; el trabajo local no equivale a una versión disponible.

## Si algo no funciona

| Problema | Qué comprobar |
| --- | --- |
| Todo sigue en inglés | Confirma el Build ID, el idioma English y que `Anvil-Spanish-Full_P.pak` está directamente en `Anvil\Content\Paks`, no dentro de otra carpeta. Comprueba que no hay una segunda localización activa. |
| Se mezclan español y ruso | Cierra el juego y desactiva el PAK de la localización anterior. Deja un solo paquete compatible con tu build. |
| Hay caracteres extraños o texto recortado | Comprueba la versión y que no queda un PAK de traducción anterior. Verifica la suma de comprobación y guarda una captura de la ventana afectada. |
| El juego no inicia | Cierra el juego y desactiva temporalmente solo el PAK de traducción. Si el error continúa sin él, utiliza la verificación de archivos de Steam. No borres `Anvil-Windows.pak`. |
| Una actualización cambió el build | Mantén desactivada la traducción hasta que haya una versión publicada compatible. |
| Hub no puede desinstalar sin conexión | Usa la desactivación temporal de la [sección de Hub](#nfg-hub) y completa la desinstalación desde Hub cuando tengas conexión. |

El paquete incluye 2 994 entradas del catálogo seleccionado; eso no significa que traduzca todos los textos del juego. Los mensajes del servidor, los textos dentro de imágenes y algunas cadenas poco frecuentes pueden seguir en inglés. La comprobación dentro del juego fue selectiva; esta versión sigue siendo beta.

### Comprobar el archivo descargado

Puedes abrir PowerShell en la carpeta del PAK extraído y ejecutar este comando, que **solo lee el archivo**:

```powershell
Get-FileHash .\Anvil-Spanish-Full_P.pak -Algorithm SHA256
```

SHA-256 esperado del PAK de ES 0.1.0:

```text
7825a8941ef0382022bbfd3abf42a5d134f0f64d49966dda355b711e1da48e22
```

Si es diferente, no instales el archivo: descarga de nuevo el paquete desde esta página. La suma del ZIP se publica junto al archivo y no es la misma que la del PAK.

## Pedir ayuda

Abre una incidencia en el [repositorio común de localizaciones](https://github.com/Aneonfas/anvil-empires-localizations/issues). Necesitas una cuenta de GitHub para enviarla. Indica el idioma y la versión del paquete, **el número Build ID**, cómo lo instalaste (manualmente o versión de Hub), los pasos antes del error y el resultado esperado. Si el problema es visual o de texto, adjunta una captura de la ventana.

No adjuntes el `appmanifest` completo, archivos del juego, datos de tu cuenta ni rutas personales completas. Para comprobar la versión basta con el número `buildid`. Usa el repositorio común también para problemas de versiones antiguas.

## Condiciones de uso

El proyecto no está afiliado a Siege Camp y no sustituye al juego. Antes de instalarlo, lee **`INFO/LICENSE_ES.txt`** dentro del ZIP. Que el archivo sea público no autoriza a republicarlo ni venderlo: comparte el enlace a la versión oficial. Aunque la licencia del ZIP antiguo mencione otro repositorio, el contacto actual es el [repositorio común](https://github.com/Aneonfas/anvil-empires-localizations).
