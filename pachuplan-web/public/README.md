# PachuPlan Web

Sitio estático oficial de PachuPlan.

## Rutas
- `/`
- `/privacidad`
- `/terminos`
- `/comunidad`
- `/eliminar-cuenta`

## Antes de publicar
Reemplaza `[CORREO_DE_SOPORTE]` en:
- privacidad.html
- terminos.html
- eliminar-cuenta.html

Puedes hacerlo en VS Code con Buscar/Reemplazar global.

## Cloudflare Pages
Este proyecto no necesita build.

Configuración recomendada:
- Framework preset: None
- Build command: dejar vacío
- Build output directory: `/` o la raíz del repositorio, según la UI vigente
- Production branch: `main`

Luego agrega `pachuplan.com` y `www.pachuplan.com` como Custom Domains.

## Git
```bash
git init
git add .
git commit -m "Initial PachuPlan website"
git branch -M main
git remote add origin <URL-DE-TU-REPO>
git push -u origin main
```
