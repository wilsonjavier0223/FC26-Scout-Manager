# FC26 Scout Manager

Aplicación web estática para registrar, evaluar, comparar y dar seguimiento a jugadores de **EA Sports FC 26**.

## Primera versión

- Dashboard de scouting.
- Registro y edición manual de jugadores.
- Evaluación orientativa con pesos configurables.
- Comparador de hasta tres candidatos.
- Estados: observación, preseleccionado, finalista y descartado.
- Contexto del club y presupuesto.
- Exportación e importación de respaldos JSON.
- Persistencia local en el navegador mediante `localStorage`.
- Interfaz responsive para móvil y escritorio.

## Ejecutar

Abre `index.html` en un navegador o publica el repositorio con GitHub Pages.

Para activar GitHub Pages:
1. Entra en **Settings → Pages** en este repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama **main** y la carpeta **/(root)**.
4. Guarda. GitHub mostrará la URL pública cuando termine el despliegue.

## Importante sobre los datos

Los informes se guardan en el navegador del dispositivo. No se sincronizan automáticamente entre dispositivos ni se almacenan en GitHub. Usa **Exportar respaldo** periódicamente y conserva el archivo JSON en un lugar seguro.

## Estado

Versión inicial en desarrollo. La puntuación es una ayuda de análisis configurable, no una decisión automática de fichaje.
