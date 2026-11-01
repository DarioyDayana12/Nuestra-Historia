# ❤️ Dario & Dayana — Nuestros Recuerdos

Página web de recuerdos para Dario y Dayana Castro.

**Fecha de inicio del noviazgo:** 12 de abril de 2026

Lista para publicar en **GitHub Pages**.

## Cómo publicarla en GitHub (paso a paso)

### 1. Crea una cuenta en GitHub (si no tienes)
Ve a [github.com](https://github.com) y regístrate.

### 2. Crea un repositorio nuevo
1. En GitHub haz clic en el botón **+** → **New repository**
2. Nombre del repositorio: `recuerdos` (o el que quieras)
3. Déjalo en **Public**
4. **NO** marques "Add a README"
5. Haz clic en **Create repository**

### 3. Sube estos archivos
Puedes hacerlo de dos formas:

**Opción fácil (desde la web):**
1. En el repositorio vacío haz clic en **uploading an existing file**
2. Arrastra **todos** los archivos y la carpeta `images`
3. Escribe un mensaje como "Primera versión de nuestros recuerdos"
4. Haz clic en **Commit changes**

**Opción con Git (si sabes usarlo):**
```bash
git init
git add .
git commit -m "Primera versión de nuestros recuerdos"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/recuerdos.git
git push -u origin main
```

### 4. Activa GitHub Pages
1. En tu repositorio ve a **Settings** → **Pages** (en el menú izquierdo)
2. En **Source** elige **Deploy from a branch**
3. Branch: `main` / folder: `/ (root)`
4. Guarda
5. Espera 1-2 minutos y tu página estará en:
   `https://TU-USUARIO.github.io/recuerdos/`

## Personalizar

### Cambiar la fecha de inicio
Abre `script.js` y busca esta línea:
```js
const startDate = new Date(2024, 5, 1); // 1 de junio 2024
```
- El mes empieza en 0 (enero = 0, febrero = 1, ..., diciembre = 11)

### Cambiar nombres y textos
Edita el archivo `index.html`:
- Título y nombres en la sección hero
- Historia en "Nuestra Historia"
- Mensaje final en "Para ti"
- Timeline de momentos especiales

### Agregar más fotos
1. Sube las fotos a la carpeta `images/`
2. Agrégalas en el array `photos` de `script.js`

## Ideas extras
- Puedes poner una contraseña sencilla después (dime y te ayudo)
- Agregar música de fondo
- Más secciones (canciones, cartas, etc.)

Hecho con cariño 💕
