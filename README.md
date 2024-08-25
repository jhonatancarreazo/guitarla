# Guitarla

Este es el código fuente de Guitarla, desarrollado con React.js. una tienda que  incluye una colección de guitarras con funcionalidades de carrito de compras.

## Tecnologías Utilizadas

- **React.js**: Biblioteca de JavaScript para construir interfaces de usuario.
- **Vite**: Herramienta de construcción rápida para proyectos web.
- **CSS**: Estilos personalizados.

## Estructura del Proyecto

- `src/`: Contiene todos los componentes y archivos principales del proyecto.
  - `components/`: Componentes reutilizables como `Header`, `Footer`, y `Guitar`.
  - `data/`: Contiene un archivo `db.js` que simula una base de datos de guitarras.
  - `App.jsx`: Componente principal de la aplicación.
  - `main.jsx`: Punto de entrada del proyecto.
- `public/`: Carpeta que contiene las imágenes y recursos públicos.

## Funcionalidades

- **Carrito de Compras**: Permite agregar, eliminar, y ajustar la cantidad de productos en el carrito.
- **Persistencia**: El estado del carrito se guarda en `localStorage` para mantener los datos entre sesiones.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jhonatancarreazo/guitarla.git
