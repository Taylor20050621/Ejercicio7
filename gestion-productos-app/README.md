# Gestión de Productos

Aplicación SPA de inventario creada con Angular y TypeScript. Incluye navegación por rutas, listado reactivo de productos, alta con `ngModel` y eliminación desde el inventario.

## Requisitos

- Node.js LTS
- npm

## Ejecutar localmente

```bash
npm install
npm start
```

Abre `http://localhost:4200`. Los productos de ejemplo y los cambios se mantienen en memoria y se restablecen al recargar la aplicación.

## Validar

```bash
npm run build
npm test -- --watch=false
```

## Estructura principal

- `src/app/models`: interfaz `Producto`.
- `src/app/services`: gestión de productos con observables RxJS y acceso HTTP opcional.
- `src/app/components`: listado y formulario.
- `src/app/app-routing-module.ts`: rutas de inventario y alta.
