# 🛍️ Mi Tienda Online - E-commerce React

Una aplicación de e-commerce moderna construida con React, Vite y CSS puro. Incluye carrito de compras funcional, interfaz responsive y diseño atractivo.

![E-commerce Screenshot](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?w=600)

## ✨ Características

- 🛒 **Carrito de Compras** - Agregar, eliminar y modificar cantidades
- 📱 **Diseño Responsive** - Funciona en desktop, tablet y móvil
- ⚡ **Rendimiento Optimizado** - Construido con Vite para máxima velocidad
- 🎨 **Interfaz Moderna** - Diseño limpio y atractivo
- 🔄 **Estado en Tiempo Real** - Actualizaciones instantáneas del carrito


## 📦 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm o yarn

### Pasos para ejecutar localmente

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/jean141818/ReactProjetc.git
   cd ReactProjetc
Instalar dependencias

bash
npm install
Ejecutar en modo desarrollo

bash
npm run dev
Abrir en el navegador

text
http://localhost:5173
Comandos disponibles
bash
npm run dev          # Servidor de desarrollo
npm run build        # Build para producción
npm run preview      # Vista previa del build
🛠️ Tecnologías Utilizadas
Frontend: React 18, Vite

Estilos: CSS3 puro (Grid, Flexbox)

Control de Estado: React Hooks (useState)

Iconos: Emojis nativos

Imágenes: Unsplash API

📁 Estructura del Proyecto
text
src/
├── components/
│   ├── Header.jsx      # Header con logo y carrito
│   ├── ProductList.jsx # Lista de productos
│   ├── ProductCard.jsx # Tarjeta individual de producto
│   └── Cart.jsx        # Modal del carrito
├── App.jsx             # Componente principal
├── main.jsx            # Punto de entrada
└── index.css           # Estilos globales
🎯 Funcionalidades Implementadas
✅ Completadas
Catálogo de productos

Agregar productos al carrito

Ver/ocultar carrito

Modificar cantidades

Eliminar productos

Cálculo de total

Diseño responsive

🔄 Próximas Features
Búsqueda y filtros

Categorías de productos

Autenticación de usuarios

Integración con API real

Pasarela de pagos

Modo oscuro

👨‍💻 Desarrollo
Componentes Principales
App.jsx
Estado global del carrito

Gestión de productos

Lógica del carrito

ProductCard.jsx
Display de producto individual

Botón "Agregar al carrito"

Información de precio y descripción

Cart.jsx
Lista de productos en carrito

Controles de cantidad

Cálculo de total

Botón de checkout

🎨 Personalización
Puedes personalizar los productos editando el array en src/App.jsx:

javascript
const products = [
  {
    id: 1,
    name: "Tu Producto",
    price: 99.99,
    image: "url-de-imagen",
    description: "Descripción del producto"
  }
];
🤝 Contribución
¡Las contribuciones son bienvenidas!

Fork el proyecto

Crea una rama feature (git checkout -b feature/AmazingFeature)

Commit tus cambios (git commit -m 'Add some AmazingFeature')

Push a la rama (git push origin feature/AmazingFeature)

Abre un Pull Request

📄 Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para detalles.

👤 Autor
Jean Noronha

GitHub: @jean141818

Proyecto: ReactProjetc

🙏 Agradecimientos
React - Biblioteca de JavaScript

Vite - Herramienta de build

Unsplash - Imágenes gratuitas
