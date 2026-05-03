# Mision Aaron

App educativa movil tipo videojuego de misiones para entrenar deberes reales con ejercicios parecidos, sin resolver el deber directamente.

## Que incluye

- React + Vite + TypeScript.
- PWA instalable en movil.
- Estado y progreso guardados en `localStorage`.
- Misiones de Lectoescritura, Matematicas, Ingles, Catala y Entrenar deberes.
- Mision fija: `Deures reals: Monedes i decimals`.
- Panel de progreso con XP, tiempo de uso, historial diario y errores frecuentes.

## Desarrollo local

```bash
npm install
npm run dev
```

Abre:

```text
http://localhost:5173/
```

## Probar version de produccion local

```bash
npm run build
npm run preview
```

Vite servira la carpeta `dist`.

## Subir gratis a Vercel

1. Crea una cuenta en https://vercel.com.
2. Sube este proyecto a GitHub.
3. En Vercel, pulsa `Add New Project`.
4. Importa el repositorio.
5. Usa estos valores:
   - Framework Preset: `Vite`
   - Build Command: `npm run build`
   - Output Directory: `dist`
6. Pulsa `Deploy`.
7. Abre la URL generada por Vercel.

Para usarla siempre desde movil, subir a Vercel y abrir la URL desde el movil. Luego pulsar Instalar app.

## Datos

La app guarda el progreso en `localStorage` del navegador:

- `dailyXP`
- `totalXP`
- `xpHistoryByDate`
- `dailyTimeSeconds`
- `totalTimeSeconds`
- `timeHistoryByDate`
- preguntas respondidas hoy
- misiones completadas hoy
- errores frecuentes

No hay login ni base de datos en esta version.
