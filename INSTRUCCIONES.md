# Instrucciones para activar GitHub Pages

## Paso 1: Descarga y actualiza tu repositorio

1. Descarga el archivo `git_helper-actualizado.zip`
2. Extrae el contenido
3. Copia la carpeta `.github` a tu repositorio local `git_helper`

## Paso 2: Sube los cambios a GitHub

Abre la terminal en la carpeta de tu proyecto y ejecuta:

```bash
git add .
git commit -m "Add GitHub Actions workflow for deployment"
git push origin main
```

## Paso 3: Configura GitHub Pages

1. Ve a tu repositorio en GitHub: https://github.com/jmcanales/git_helper
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, haz clic en **Pages**
4. En **Source**, selecciona **GitHub Actions**
5. ¡Listo! No necesitas hacer clic en Save, se guarda automáticamente

## Paso 4: Verifica el deployment

1. Ve a la pestaña **Actions** en tu repositorio
2. Deberías ver un nuevo workflow ejecutándose llamado "Deploy static content to Pages"
3. Espera a que termine (suele tomar 1-2 minutos)
4. Cuando tenga una marca verde ✅, tu sitio estará listo

## Tu sitio estará disponible en:

https://jmcanales.github.io/git_helper/

## Si tienes problemas:

- Asegúrate de que el repositorio sea público
- Verifica que la carpeta `.github` esté en la raíz del proyecto
- Revisa los logs del workflow en la pestaña Actions si falla
