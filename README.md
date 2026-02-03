# Odoo Local Dev — Guia de Entorno

by **Adroc**

---

Guia interactiva para montar un entorno de desarrollo local de Odoo con Docker y Docker Compose.

Cubre **Windows (WSL 2)**, **Linux** y **macOS**.

## Ver la guia

**[Abrir guia online](https://TU_USUARIO.github.io/odoo-local-dev/)**

## Deploy a GitHub Pages

1. Crear un repositorio en GitHub (ej: `odoo-local-dev`)

2. Subir los archivos:

```bash
cd odoo-local-guide
git init
git add .
git commit -m "Initial commit - Odoo Local Dev Guide"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/odoo-local-dev.git
git push -u origin main
```

3. Activar GitHub Pages:
   - Ve a **Settings > Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
   - Click **Save**

4. En ~1 minuto tu guia estara en:
   ```
   https://TU_USUARIO.github.io/odoo-local-dev/
   ```

## Estructura

```
odoo-local-guide/
├── index.html          # Guia completa (single-page, self-contained)
└── README.md           # Este archivo
```

## Features

- Dark theme optimizado para developers
- Botones de **copiar** en cada bloque de codigo
- Tabs por sistema operativo (Windows / Linux / macOS)
- Responsive — funciona en movil y desktop
- Sidebar con navegacion y scroll tracking
- Barra de progreso de lectura
- Zero dependencies — un solo archivo HTML
- Iconos via [Phosphor Icons](https://phosphoricons.com/)
- Print-friendly

## Contenido

1. Requisitos previos
2. Instalacion de Docker (por OS)
3. Configuracion de VS Code
4. Estructura del proyecto
5. Archivo odoo.conf
6. Dockerfile (Enterprise)
7. Docker Compose — Community
8. Docker Compose — Enterprise
9. Levantar el entorno
10. Acceder a Odoo
11. Hot Reload
12. Multiples instancias
13. Comandos utiles
14. Troubleshooting

---

`docker compose up -d`
