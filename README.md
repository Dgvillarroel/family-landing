# family-landing

Página de inicio de la familia con enlaces a:

- Menú familiar
- Estilista familiar
- Viajes en familia

Sitio estático servido por un mini servidor Node sin dependencias (`server.js`).

## Local

```
npm start
```

Abre http://localhost:3000

## Despliegue en Railway

1. Subir el repositorio a GitHub.
2. En Railway: New Project → Deploy from GitHub repo → elegir este repositorio.
3. Settings → Networking → Generate Domain.

Railway detecta Node y ejecuta `npm start` automáticamente.
