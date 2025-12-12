# Cerebro Extendido · Pancho v1.0 (PWA)

Plataforma personal para TDAH orientada a **arquitectura externa**:
- INBOX (captura rápida)
- Hoy (método 1–3–5)
- Bloques por modo (Crear/Construir/Gestionar/Cuidar)
- Proyectos activos (máximo 3) + Incubadora
- Manual Pancho v1.0 (documento vivo)
- Datos diarios + gráfico simple + export CSV

## Cómo usar (GitHub Pages)
1. Sube este repo a GitHub.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. Abre la URL de GitHub Pages.
4. Recomendado: abre cada sección una vez para que quede cacheada (offline).

## Datos y privacidad
- Todo se guarda en el navegador (localStorage).
- Puedes exportar/importar un backup JSON desde la barra superior.

## Integración opcional con Google Sheets
- En **Datos** puedes exportar CSV y subirlo a Drive.
- Si quieres recepción automática, se puede agregar un endpoint con Apps Script (no incluido por defecto).

## Estructura
- `/index.html` Dashboard
- `/pages/weekly.html` Revisión semanal
- `/pages/manual.html` Manual personal
- `/pages/data.html` Métricas

NeoTech EduLab
