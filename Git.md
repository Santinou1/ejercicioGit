
# 📖 **Guía para entender Git como un álbum de fotos** 

Esta es una explicación súper fácil de cómo funciona Git, usando una analogía de un álbum de fotos, para que puedas entenderlo mejor y ser un experto. 

---

## 🎨 **Tabla de contenido:**

1. [¿Qué es Git?](#qué-es-git)
2. [Pasos básicos para usar Git](#pasos-básicos-para-usar-git)
    - `git init`
    - `git add`
    - `git commit`
    - `git push`
3. [Qué significan las letras en Visual Studio Code](#qué-significan-las-letras-en-visual-studio-code)
    - `U = Untracked (No rastreado)`
    - `M = Modified (Modificado)`
    - `A = Added (Añadido)`
4. [Conclusión](#conclusión)

---

## 🖼️ **¿Qué es Git?**

Git es una herramienta que usamos para organizar y controlar versiones de proyectos de código. Vamos a explicarlo usando la siguiente analogía:

**Analogía:** Imagina que Git es como un álbum de fotos. Cada vez que tomas una foto, decides si ponerla en el álbum, hacer algunos retoques y finalmente subirla a la nube para compartirla con tus amigos.

---

## 🚀 **Pasos básicos para usar Git**

### 🌱 `git init` = Empezar el álbum de fotos

Este comando es como crear un álbum de fotos vacío donde empezarás a pegar tus fotos (o archivos del proyecto).

- **Cómo hacerlo:**
    ```bash
    git init
    ```
    ¡Y listo! Ahora tienes un álbum vacío (repositorio).

---

### 📸 `git add` = Escoger fotos para el álbum

Cuando haces cambios en tus archivos, es como si tomaras nuevas fotos. El comando `git add` es como seleccionar qué fotos quieres pegar en el álbum.

- **Cómo hacerlo en VS Code:**
    - Puedes usar la terminal: 
        ```bash
        git add .
        ```
    - O ir a la barra lateral en Visual Studio Code y presionar el símbolo de **+** junto a los archivos.

---

### 🖼️ `git commit` = Guardar las fotos en el álbum

Este comando es como pegar tus fotos en el álbum y escribir una pequeña nota sobre ellas. Cada commit es como una página del álbum con un mensaje que describe qué hiciste.

- **Cómo hacerlo en VS Code:**
    - Escribe un mensaje de commit en VS Code o usa la terminal:
        ```bash
        git commit -m "Añadí fotos del viaje"
        ```

---

### ☁️ `git push` = Subir el álbum a la nube

Una vez que tienes tus fotos en el álbum (los commits), es hora de subir todo a la nube para guardarlo o compartirlo. `git push` hace exactamente eso.

- **Cómo hacerlo en la terminal:**
    ```bash
    git push origin main
    ```

---

## 🔠 **Qué significan las letras en Visual Studio Code**

En Visual Studio Code, verás letras como **U**, **M** y **A** al lado de tus archivos. Estas letras te indican en qué estado se encuentran tus archivos:

### 📂 `U = Untracked (No rastreado)`
Esto aparece cuando Git ve un archivo nuevo que aún no está siendo controlado. Es como tomar una nueva foto, pero aún no la has puesto en el álbum.

**Analogía:** Imagina que tomaste una nueva foto, pero todavía no decidiste si la vas a pegar en tu álbum o no. Git se dio cuenta de que esa "foto" (archivo) existe, pero como no la has agregado aún, no la está rastreando.

- **Cómo solucionarlo:** Usa `git add` para que Git lo empiece a rastrear.

### ✍️ `M = Modified (Modificado)`
Esto aparece cuando has hecho cambios en un archivo que ya está en tu álbum. Git sabe que lo cambiaste, pero no lo has guardado todavía.

**Analogía:** Tienes una foto que ya está en el álbum, pero decidiste hacerle algunos retoques o cambiarle algo. Git sabe que hiciste estos cambios, pero todavía no los has guardado permanentemente en el álbum.

- **Cómo solucionarlo:** Usa `git add` y luego `git commit` para guardar los cambios.

### 📎 `A = Added (Añadido)`
Esto aparece cuando has añadido un archivo nuevo a Git usando `git add`, pero aún no lo has guardado en el álbum (commit).

**Analogía:** Ya seleccionaste una nueva foto y la pusiste en el álbum (usando `git add`), pero aún no la has pegado de forma permanente. Está lista, pero no ha sido guardada oficialmente en el historial del álbum.

- **Cómo solucionarlo:** Haz un `git commit` para guardar el archivo en el historial.

---

## ✅ **Conclusión**

Git te ayuda a organizar y controlar tu código como si estuvieras haciendo un álbum de fotos. Recuerda los pasos: 
1. Inicia tu álbum con `git init`.
2. Elige las fotos con `git add`.
3. Pega las fotos con `git commit`.
4. Sube tu álbum a la nube con `git push`.

¡Y eso es todo! Ahora puedes manejar tus proyectos en Git con facilidad. 🖥️📚
