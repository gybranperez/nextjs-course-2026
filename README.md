# nextjs-course-2026

Curso de Next.js 2026 con ejemplos prácticos y aplicaciones web modernas.

## 📦 Contenido del Proyecto

- **001webapp/first-steps**: Aplicación inicial de Next.js con TypeScript y Tailwind CSS
  - Páginas: Home, About
  - Configuración de rutas y layouts
  - Estilos con Tailwind CSS v4

## 🛠️ Tecnologías y Versiones

- **Next.js**: 16.1.6
- **React**: 19.2.3
- **TypeScript**: ^5
- **Tailwind CSS**: ^4
- **ESLint**: ^9
- **Node.js**: ^20

## 🚀 Cómo Ejecutar

### Desarrollo

```bash
cd 001webapp/first-steps
npm install
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## 🏗️ Cómo Construir

```bash
cd 001webapp/first-steps
npm run build
```

Genera la versión optimizada para producción en la carpeta `.next`.

## ▶️ Ejecutar en Producción

```bash
npm run start
```

Inicia el servidor de producción después de construir.

## ✅ Validar y Probar

### Linting

```bash
npm run lint
```

Valida el código con ESLint.

### Verificar Build

```bash
npm run build && npm run start
```

Construye y ejecuta para verificar que todo funciona correctamente. 
