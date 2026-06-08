# GymApp Presupuesto

Plataforma web moderna de gestión de clases para estudios de pilates y entrenamiento funcional.

## Descripción

Aplicación web progresiva (PWA) que permite a los alumnos gestionar sus asistencias y cambios de horario de forma independiente, eliminando la coordinación manual.

### Características principales

- **Gestión de clases**: Visualización de horarios y confirmación/cancelación de asistencia
- **Reasignación automática de cupos**: Los cupos liberados se reasignan automáticamente
- **Lista de espera inteligente**: Notificaciones automáticas cuando se libera un lugar
- **Panel de administración**: Visibilidad completa del estado de clases y alumnos
- **Notificaciones automáticas**: Recordatorios y confirmaciones sin intervención manual
- **Mobile First**: Aplicación PWA con experiencia nativa en cualquier dispositivo

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── Logotipo.png       # Logo de Tricode
├── README.md          # Este archivo
├── .gitignore         # Exclusiones de Git
├── vercel.json        # Configuración de Vercel
└── package.json       # Metadatos del proyecto
```

## Requisitos

- Navegador moderno con soporte para:
  - CSS Grid y Flexbox
  - ES6 JavaScript
  - Intersection Observer API

## Desarrollo Local

```bash
python3 -m http.server 3000
```

Luego abre [http://localhost:3000](http://localhost:3000)

## Deployment

Optimizado para Vercel:

```bash
npm install -g vercel
vercel
```

## Especificaciones Técnicas

- **Frontend**: HTML5, CSS3 (Glassmorphism, Gradientes, Animaciones)
- **JavaScript**: ES6 Vanilla (sin frameworks)
- **Fuentes**: Inter (body), Space Grotesk (display)
- **Responsive**: Mobile First, 100% responsive

## Autor

**Tricode** - Soluciones digitales para profesionales del fitness

## Licencia

Confidencial
