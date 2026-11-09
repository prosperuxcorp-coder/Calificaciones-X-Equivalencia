# Dashboard — Calificación por equivalencia 2026–2027

## Metas
- **Período:** noviembre de 2026 a agosto de 2027 (10 meses).
- **Meta mensual:** 9,000.
- **Meta total:** 90,000.

## Funciones
- Registro editable de los resultados mensuales.
- Avance y gráfico mensual dinámicos.
- Diferencia respecto a la meta y promedio necesario por mes restante, usando un mes de corte seleccionable.
- Almacenamiento local en el navegador.
- Exportación CSV, respaldo e importación JSON.
- Diseño adaptado para móvil y computadora, sin dependencias externas.

## Publicar gratis en GitHub Pages
1. Crea un repositorio público nuevo en GitHub (ejemplo: `equivalencia-dashboard`).
2. Sube `index.html` a la **raíz** del repositorio (README.md es opcional).
3. Ve a **Settings → Pages → Build and deployment**.
4. Selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.
5. GitHub mostrará la URL de tu página en la sección Pages cuando termine la publicación: `https://TU-USUARIO.github.io/equivalencia-dashboard/` si mantienes ese nombre de repositorio.

**Importante:** Los registros se guardan en cada navegador/dispositivo mediante `localStorage`, no en GitHub. Para pasar información de un dispositivo a otro, descarga un respaldo JSON e impórtalo allí. No guardes datos privados en el código público del repositorio.

**Nota:** Se usan unidades sin especificar (PV, puntos, etc.), ya que la meta fue indicada como 90,000 sin una unidad concreta.
