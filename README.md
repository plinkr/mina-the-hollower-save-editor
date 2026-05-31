# Mina the Hollower - Bones Save Editor

[**Read in English**](#english) | [**Leer en Español**](#español)

---

<a id="english"></a>
## English

A simple, lightweight, browser-based save editor for **Mina the Hollower**. This tool allows you to modify the amount of **Bones** (the primary in-game currency) in your `saveData.yc` file. 

Since it runs entirely in your web browser using HTML and JavaScript, **no installation is required** and your save file is processed locally on your machine (no data is uploaded to any server). The interface automatically adapts to English or Spanish based on your browser's language.

### Disclaimer
**ALWAYS BACKUP YOUR ORIGINAL SAVE FILE BEFORE EDITING!** If your save file becomes corrupted, the game usually creates an automatic backup called `saveData.bak.yc`. You can delete the corrupted file and rename the `.bak.yc` to `saveData.yc` to restore your progress.

### Where to find your save file (`saveData.yc`)
Depending on your platform, your save file is located here:
* **Windows:** `%LOCALAPPDATA%\Yacht Club Games\Mina the Hollower\`
* **Steam (Windows):** `C:\Program Files (x86)\Steam\userdata\<YourSteamID>\1875580\remote\`
* **macOS:** `~/Library/Application Support/Yacht Club Games/Mina the Hollower/`
* **Linux:** `~/.local/share/Yacht Club Games/Mina the Hollower/`
* **Nintendo Switch:** Inside the `0100DCD01F306000` folder *(Requires a modded console and a save manager like JKSV or Checkpoint).*

### How to use
1. Go to the [web editor page](https://plinkr.github.io/mina-the-hollower-save-editor).
2. Click "Upload your file" and select your `saveData.yc` file.
3. Enter the desired amount of Bones (Max: 99999).
4. Click **"Apply & Download"**.
5. Replace your original `saveData.yc` file with the newly downloaded one.

---

<a id="español"></a>
## Español

Un editor de partidas ligero y basado en el navegador para **Mina the Hollower**. Esta herramienta te permite modificar la cantidad de **Huesos (Bones)** (la moneda principal del juego) en tu archivo `saveData.yc`.

Dado que funciona completamente en tu navegador web mediante HTML y JavaScript, **no requiere instalación** y tu archivo se procesa de forma local en tu equipo (no se sube ningún dato a internet). La interfaz se adapta automáticamente a inglés o español según el idioma de tu navegador.

### Advertencia
**¡HAZ SIEMPRE UNA COPIA DE SEGURIDAD DE TU PARTIDA ANTES DE EDITARLA!**
Si tu partida se corrompe por algún error, el juego suele crear un archivo de respaldo automático llamado `saveData.bak.yc`. Puedes borrar el archivo defectuoso y renombrar el `.bak.yc` a `saveData.yc` para restaurar tu progreso.

### Dónde encontrar tu partida (`saveData.yc`)
Dependiendo de tu plataforma, tu archivo de guardado se encuentra aquí:
* **Windows:** `%LOCALAPPDATA%\Yacht Club Games\Mina the Hollower\`
* **Steam (Windows):** `C:\Program Files (x86)\Steam\userdata\<TuSteamID>\1875580\remote\`
* **macOS:** `~/Library/Application Support/Yacht Club Games/Mina the Hollower/`
* **Linux:** `~/.local/share/Yacht Club Games/Mina the Hollower/`
* **Nintendo Switch:** Dentro de la carpeta `0100DCD01F306000` *(Requiere una consola modificada y un gestor de guardado como JKSV o Checkpoint).*

### Cómo usarlo
1. Ve a la [página del editor web](https://plinkr.github.io/mina-the-hollower-save-editor).
2. Haz clic en "Sube tu archivo" y selecciona tu archivo `saveData.yc`.
3. Introduce la cantidad de Huesos que deseas (Máximo: 99999).
4. Haz clic en **"Aplicar y Descargar"**.
5. Reemplaza tu archivo `saveData.yc` original por el que se acaba de descargar.