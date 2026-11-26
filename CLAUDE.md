# Listado de contadores

App de un solo `index.html`, sin build. Se publica con GitHub Pages desde `main`: https://iaelicozzolino-boop.github.io/listado-contadores/

- Las lecturas se guardan en `localStorage` (`readings_<fecha>`), solo en cada navegador. Todas las apps de `iaelicozzolino-boop.github.io` comparten origen.
- PDF con jsPDF y jspdf-autotable desde jsDelivr (necesita conexión la primera vez).
- La lista de contadores del puerto está en el propio `index.html`.
- `v4/index.html` solo redirige a la raíz, por si quedan enlaces o accesos directos antiguos. No volver a duplicar la app ahí.
- Enlazada desde el repo MarinaIbizaApps.
