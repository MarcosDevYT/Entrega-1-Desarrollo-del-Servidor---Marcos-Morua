# Entregable-1-Marcos-Morua

Primer entregable para Backend 1 - Coderhouse, de Marcos Morua, en esta entrega se crean las clases de CartManager y ProductManager para crear, editar, eliminar y obtener productos o carritos. Se utiliza el Router de Express para utilizar las rutas de los archivos cart.js y product.js.

## Estructura del Proyecto

```
Entregable-1-Marcos-Morua
├── app
|   |
│   ├── modules
|   |   └── ProductManager.js # Clase para gestionar productos
│   │
│   ├── routes
│   │   └── products.js       # Rutas relacionadas con productos
│   └── data
│       └── products.json     # Archivo JSON para persistencia de productos
|
├── index.js                  # Punto de entrada de la aplicación
├── package.json              # Configuración de npm
└── README.md                 # Documentación del proyecto
```

## Uso

1. Inicia el servidor:

   ```
   npm run dev (Para iniciar con nodemon)
   npm run server (Para iniciar con Node)
   ```

2. Accede a la API en `http://localhost:8080`.

## Endpoints

Los Enpoints estan en el json llamado Backend 1 - Marcos Morua.postman_collection, donde estan todas las solicitudes HTTP hechas en Postman
