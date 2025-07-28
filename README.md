# J&C Studios - Website Corporativo

Sitio web moderno y profesional para J&C Studios, una empresa especializada en servicios digitales y creativos incluyendo desarrollo web, diseño de logos, edición de video, identidad visual y consultoría tecnológica.

## 🚀 Características

- **Diseño Moderno**: Interfaz elegante con gradientes dorados y animaciones fluidas
- **Totalmente Responsivo**: Optimizado para desktop, tablet y móvil
- **Animaciones Premium**: Efectos suaves con Framer Motion
- **Rendimiento Optimizado**: Construido con Vite para máxima velocidad
- **SEO Friendly**: Estructura semántica y meta tags optimizados
- **Accessible**: Cumple con estándares de accesibilidad web

## 🛠️ Tecnologías Utilizadas

- **React 18** - Framework de UI moderno
- **TypeScript** - Tipado estático para mejor desarrollo
- **Vite** - Build tool súper rápido
- **Tailwind CSS** - Framework de CSS utility-first
- **Framer Motion** - Librería de animaciones
- **Lucide React** - Iconos modernos y ligeros
- **React Icons** - Iconos de redes sociales

## 📦 Instalación y Configuración

### Prerrequisitos
- Node.js (versión 18 o superior)
- npm o yarn

### Pasos de instalación

1. **Clonar el repositorio**
   ```bash
   git clone <repository-url>
   cd "J&C Studios"
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

4. **Construir para producción**
   ```bash
   npm run build
   ```

5. **Preview de la construcción**
   ```bash
   npm run preview
   ```

## 🎨 Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── Navbar.tsx      # Barra de navegación
│   └── Footer.tsx      # Pie de página
├── sections/           # Secciones principales
│   ├── Hero.tsx        # Sección de bienvenida
│   ├── Services.tsx    # Servicios ofrecidos
│   ├── Portfolio.tsx   # Portafolio de proyectos
│   └── Contact.tsx     # Formulario de contacto
├── assets/            # Recursos estáticos
├── App.tsx            # Componente principal
├── main.tsx          # Punto de entrada
└── index.css         # Estilos globales
```

## 🎯 Secciones del Sitio

1. **Hero Section** - Presentación principal con call-to-action
2. **Services** - Cards de servicios con iconos y descripciones
3. **Portfolio** - Galería de proyectos realizados
4. **Contact** - Formulario de contacto y información
5. **Footer** - Links, newsletter y redes sociales

## 🎨 Paleta de Colores

- **Primario**: Tonos dorados (#f59e0b, #fbbf24, #fcd34d)
- **Secundario**: Escalas de grises
- **Fondo**: Blanco y negro
- **Acentos**: Gradientes creativos

## 📱 Responsive Design

El sitio está optimizado para:
- **Desktop**: 1024px+
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## 🔧 Comandos Disponibles

```bash
npm run dev          # Servidor de desarrollo
npm run build        # Construir para producción
npm run preview      # Preview de la construcción
npm run lint         # Ejecutar ESLint
```

## 📧 Contacto

Para consultas sobre el proyecto:
- **Email**: dczl0603@gmail.com   
- **WhatsApp**: +51 926206841
- **Website**: [J&C Studios](https://jcstudios.com)

## 📄 Licencia

Este proyecto es propriedad de J&C Studios. Todos los derechos reservados.

---

Desarrollado con ❤️ por J&C Studios

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      ...tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      ...tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      ...tseslint.configs.stylisticTypeChecked,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```
