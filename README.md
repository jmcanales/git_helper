# git-cheatsheet

comandos de git que siempre olvido y termino googleando

## 🌐 ver online

https://tu-usuario.github.io/git-cheatsheet

## 🚀 como subir esto a github pages

1. crear repo en github con el nombre `git-cheatsheet`

2. subir el código:
```bash
git init
git add .
git commit -m "primer commit"
git branch -M main
git remote add origin https://github.com/tu-usuario/git-cheatsheet.git
git push -u origin main
```

3. en github → settings → pages
   - source: deploy from a branch
   - branch: main, carpeta: / (root)
   - save

4. esperar 1-2 minutos y listo

## 📝 contenido

- comandos básicos del día a día
- como trabajar con ramas
- como arreglar cagadas comunes
- extras que uso de vez en cuando

## 🎨 personalizar

todo está en `index.html`

los colores están en la sección `:root` del CSS si querés cambiarlos

## 💡 inspiración

basado en experiencias reales de googlear "git undo commit" por 47ma vez

---

**nombre sugerido del repo:** git-cheatsheet

**url final:** https://tu-usuario.github.io/git-cheatsheet
