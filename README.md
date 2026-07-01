# Cozy An Boutique Hotel — Website Concept

Propuesta de rediseño web para Cozy An Boutique Hotel (Hội An, Vietnam), creada como
demo para mostrar al hotel antes de ofrecer el servicio.

## Deploy en Vercel

1. Sube este repo a GitHub (ver comandos abajo).
2. Entra a vercel.com → "Add New Project" → conecta este repo → Deploy.
   No requiere build step, es HTML/CSS/JS puro.

## Editar fotos

Cada bloque marcado como placeholder tiene una etiqueta `Photo brief — ...`
indicando qué foto va ahí. Busca la clase `.ph` en `index.html` y reemplaza
ese `<div class="ph">` por `<img src="tu-foto.jpg" alt="...">`.

## Comandos para subir a GitHub

```bash
cd cozyan-repo
git init
git add .
git commit -m "Cozy An Boutique Hotel - website concept"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/cozy-an-concept.git
git push -u origin main
```
