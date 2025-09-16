# 📂 Portafolio de Proyectos – Juan David Montenegro

¡Bienvenido a mi portafolio personal! Este es un espacio donde muestro mis proyectos, habilidades y experiencia en el Desarrollo de software. Desarrollado con **Angular 18**  y **TypeScript**, este portafolio sirve como plataforma central donde hospedo y presento todos mis proyectos.

---

## 🎯 Sobre el Portafolio

Este portafolio está diseñado para:
- **Mostrar mis proyectos**: Una colección completa de mis trabajos en Desarrollo frontend y backend
- **Demostrar habilidades**: Experiencia práctica con tecnologías modernas
- **Facilitar contacto**: Información profesional y medios de contacto
- **Hosting centralizado**: Todos mis proyectos alojados en un solo lugar

---

## 🚀 Tecnologías Utilizadas

### Frontend
- **Angular 18** - Framework principal
- **TypeScript** - Lenguaje de programación
- **SCSS** - Preprocesador CSS
- **RxJS** - Programación reactiva
- **HTML5 / CSS3** - Estructura y estilos

### Herramientas de Desarrollo
- **Angular CLI** - Herramientas de Desarrollo
- **Angular Material** - Herramienta de Desarrollo
---
### Backend
- **Nestjs** - Framework principal
- **TypeScript** - Lenguaje de programación

### Herramientas de Desarrollo
- **Nestjs CLI** - Herramientas de Desarrollo
---

## 📋 Requisitos Previos

Antes de instalar y ejecutar el proyecto, asegúrate de tener instalado:

- **Node.js** (versión 18 o superior)
- **npm** (incluido con Node.js)
- **Git** (para clonar el repositorio)

### Verificar instalaciones:
```bash
node --version
```
```bash
npm --version
```
```bash
git --version
```

---

## 📦 Instalación

Sigue estos pasos para ejecutar el proyecto en tu máquina local:

### 1. Clonar el repositorio
```bash
git clone https://github.com/juandavidmontenegro/Portafolio.git
```
### 2. Entra la Carpeta del proyecto
```bash
cd Portafolio
```
### 3. Instalar dependencias
```bash
npm install
```

### 4. Verificar la instalación
```bash
npm list --depth=0
```
---

## Ejecución del Proyecto

### Desarrollo (Modo Local)
Para ejecutar el proyecto en modo Desarrollo:
```bash
ng s --open
```

El servidor de Desarrollo se iniciará en el navegador con la url
```bash
http://localhost:4200/
```
### Producción (Build)
Para crear una versión optimizada para producción:

```bash
npm run build
```

Los archivos compilados se guardarán en el directorio `dist/`

### Testing
Para ejecutar las pruebas unitarias:

```bash
npm test
```

Para ejecutar las pruebas en modo watch:
```bash
ng test --watch
```

---

## �️ Estructura del Proyecto

```
Portafolio/
├── src/
│   ├── app/                 # Componentes de la aplicación
│   │   ├── app.config.ts    # Configuración de la app
│   │   ├── app.routes.ts    # Rutas de navegación
│   │   ├── app.ts           # Componente principal
│   │   └── app.scss         # Estilos globales del componente
│   ├── index.html           # Página principal
│   ├── main.ts              # Punto de entrada de la aplicación
│   └── styles.scss          # Estilos globales
├── public/                  # Archivos estáticos
│   └── favicon.ico          # Icono de la aplicación
├── angular.json             # Configuración de Angular CLI
├── package.json             # Dependencias y scripts
├── tsconfig.json            # Configuración de TypeScript
└── README.md                # Este archivo
```

---

## 🌐 Proyectos Hospedados

Este portafolio sirve como hub central para todos mis proyectos. Aquí podrás encontrar:

### Proyectos Frontend
- **Aplicaciones Angular**: SPAs con funcionalidades avanzadas
- **Proyectos React**: Componentes reutilizables y hooks
- **Vanilla JavaScript**: Proyectos puros sin frameworks

### Proyectos Backend
- **APIs REST**: Servicios web con Node.js y Express
- **Bases de Datos**: Integración con MongoDB, MySQL, PostgreSQL
- **Microservicios**: Arquitecturas distribuidas

### Proyectos Full-Stack
- **E-commerce**: Plataformas completas de comercio electrónico
- **Dashboards**: Paneles de administración y analytics
- **Sistemas de Gestión**: CRMs y ERPs personalizados

### 🔗 Enlaces Directos
Cada proyecto incluye:
- **Demo en vivo**: Enlace directo a la aplicación funcionando
- **Código fuente**: Repositorio en GitHub
- **Documentación**: Instrucciones detalladas de instalación y uso
- **Tecnologías**: Stack tecnológico utilizado

---

## 🚀 Despliegue en Producción

### Opciones de Hosting

#### 1. Netlify (Recomendado para frontend)
```bash
# Build del proyecto
npm run build

# Deploy manual: subir carpeta dist/ a Netlify
# Deploy automático: conectar repositorio de GitHub
```

#### 2. Vercel
```bash
# Instalar Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

#### 3. GitHub Pages
```bash
# Instalar angular-cli-ghpages
npm install -g angular-cli-ghpages

# Build y deploy
ng build --configuration production --base-href="https://juandavidmontenegro.github.io/Portafolio/"
npx angular-cli-ghpages --dir=dist/portafolio
```

#### 4. Firebase Hosting
```bash
# Instalar Firebase CLI
npm install -g firebase-tools

# Inicializar proyecto
firebase init hosting

# Deploy
npm run build
firebase deploy
```

### Variables de Entorno
Para configuraciones específicas de producción, crea archivos de entorno:

```typescript
// src/environments/environment.prod.ts
export const environment = {
  production: true,
  apiUrl: 'https://api.tudominio.com',
  // otras configuraciones...
};
```

---

## 🛠️ Scripts Disponibles

| Comando | Descripción |
|---------|-------------|
| `npm start` | Inicia el servidor de Desarrollo |
| `npm run build` | Construye la aplicación para producción |
| `npm run watch` | Construye en modo watch para Desarrollo |
| `npm test` | Ejecuta las pruebas unitarias |
| `npm run ng` | Ejecuta comandos de Angular CLI |

---

## 🤝 Contribución

Si deseas contribuir a este proyecto:

1. **Fork** el repositorio
2. Crea una **rama feature** (`git checkout -b feature/nueva-funcionalidad`)
3. **Commit** tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. **Push** a la rama (`git push origin feature/nueva-funcionalidad`)
5. Crea un **Pull Request**

---

## 📞 Contacto

- **GitHub**: [@juandavidmontenegro](https://github.com/juandavidmontenegro)
- **LinkedIn**: [Juan David Montenegro](https://linkedin.com/in/juandavidmontenegro)
- **Email**: [tu-email@ejemplo.com](mailto:tu-email@ejemplo.com)
- **Portafolio**: [https://juandavidmontenegro.github.io/Portafolio/](https://juandavidmontenegro.github.io/Portafolio/)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## 🆕 Actualizaciones Recientes

- **v1.0.0**: Lanzamiento inicial del portafolio
- **Angular 20**: Actualización a la última versión estable
- **Responsive Design**: Optimización para dispositivos móviles
- **Performance**: Mejoras en tiempo de carga y SEO

---

⭐ **¡Si te gusta este proyecto, no olvides darle una estrella en GitHub!** ⭐ 


