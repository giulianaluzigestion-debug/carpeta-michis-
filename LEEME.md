# Carpeta de michis — instrucciones para publicar

Esta carpeta tiene los 2 archivos que necesitás subir a GitHub:

- `index.html` → la app completa (ya configurada con tu base de datos de Supabase)
- `portada-michis.png` → la imagen que se va a ver al compartir el link

## Paso 1: Crear el repositorio en GitHub

1. Entrá a **https://github.com/new**
2. **Repository name**: escribí exactamente `carpeta-michis`
3. Dejalo en **Public**
4. NO marques ninguna casilla extra (ni README, ni .gitignore, ni licencia)
5. Click en **"Create repository"**

## Paso 2: Subir los archivos

En la página que se abre después de crear el repo:

1. Click en el link **"uploading an existing file"**
2. Arrastrá los dos archivos de esta carpeta: `index.html` y `portada-michis.png`
3. Abajo, en "Commit changes", dejá todo como está y click en **"Commit changes"**

## Paso 3: Activar GitHub Pages

1. En el repositorio, click en la pestaña **"Settings"** (arriba)
2. En el menú de la izquierda, click en **"Pages"**
3. En "Source", elegí **"Deploy from a branch"**
4. En "Branch", elegí **`main`** y la carpeta **`/ (root)`**
5. Click en **"Save"**

GitHub tarda 1-2 minutos en publicar todo.

## Tu app va a estar viva en:

```
https://giulianaluzigestion-debug.github.io/carpeta-michis/
```

## Sobre la base de datos (ya está lista, no necesitás hacer nada más)

La app ya está conectada a tu proyecto de **Supabase** (no Firebase — cambiamos a Supabase porque Firebase pedía vincular una tarjeta). Los datos de todas las usuarias y sus michis se guardan ahí, compartidos en tiempo real entre quien entre con su nombre.

- Proyecto: `nmkevimweutvjescxase`
- Tabla: `cats_data`

Si en algún momento necesitás revisar o borrar datos a mano, podés entrar a tu proyecto en **https://supabase.com/dashboard** → Table Editor → `cats_data`.

## Si en el futuro querés actualizar la app

Cuando yo te pase una versión nueva del `index.html`:

1. Entrá a tu repositorio en GitHub
2. Click en el archivo `index.html`
3. Click en el ícono de lápiz (editar) o "Upload files" para reemplazarlo
4. Subí el archivo nuevo con el mismo nombre `index.html`
5. Commit changes

GitHub Pages se actualiza solo, en 1-2 minutos.
