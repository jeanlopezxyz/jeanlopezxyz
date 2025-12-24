# GitHub Profile - Documentación

## Cómo funciona

Este repo (`jeanlopezxyz/jeanlopezxyz`) es especial en GitHub. El archivo `README.md` aparece automáticamente en tu perfil: https://github.com/jeanlopezxyz

## Ubicación local

```
~/github-profile/
```

## Modificar el perfil

```bash
# 1. Ir al directorio
cd ~/github-profile

# 2. Editar el README
code README.md   # o nano/vim

# 3. Guardar y subir
git add .
git commit -m "Update profile"
git push
```

## Estructura del README

| Sección | Descripción |
|---------|-------------|
| Typing SVG | Texto animado con tu nombre |
| Badges | Links a blog y LinkedIn |
| Snake | Animación de contribuciones (auto-generada) |
| About Me | Info en formato YAML |
| Tech Stack | Badges de tecnologías |
| Featured Projects | Cards de repos MCP |
| GitHub Stats | Estadísticas automáticas |
| Activity Graph | Gráfico de actividad |

## Snake Animation

Se genera automáticamente cada día a las 00:00 UTC via GitHub Actions.

**Archivo workflow:** `.github/workflows/snake.yml`

Para regenerar manualmente:
```bash
gh workflow run snake.yml --repo jeanlopezxyz/jeanlopezxyz
```

## Servicios externos usados

| Servicio | URL | Qué hace |
|----------|-----|----------|
| readme-typing-svg | demolab.com | Texto animado |
| github-readme-stats | vercel.app | Stats y repo cards |
| github-readme-streak-stats | herokuapp.com | Streak de commits |
| github-profile-trophy | vercel.app | Trofeos |
| github-readme-activity-graph | vercel.app | Gráfico actividad |
| shields.io | shields.io | Badges |
| Platane/snk | GitHub Action | Snake animation |

## Personalización

### Cambiar colores
El color principal es `#22c55e` (verde). Busca y reemplaza para cambiar.

### Agregar/quitar secciones
Edita directamente el README.md.

### Cambiar repos destacados
Modifica las URLs en la sección "Featured Projects".

## Links útiles

- Perfil: https://github.com/jeanlopezxyz
- Repo: https://github.com/jeanlopezxyz/jeanlopezxyz
- Snake branch: https://github.com/jeanlopezxyz/jeanlopezxyz/tree/output
