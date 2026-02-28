# Investigacion-Aplicada-1
Guía de Instalación - Tienda de Tecnología (Teórico 1)
Este proyecto es una aplicación de comercio electrónico desarrollada con Next.js y React. Sigue estos pasos para configurar el entorno de desarrollo.

 Requisitos Previos
Antes de comenzar, asegúrate de tener instalado:

Node.js (Versión 18 o superior).

npm (Viene incluido con Node.js).

Visual Studio Code.

🛠️ Paso 1: Instalación de Dependencias
Abre una terminal en la carpeta de tu proyecto (teorico1) y ejecuta los siguientes comandos:

1. Iniciar el proyecto (Si aún no tienes el package.json)
npm init -y
2. Instalar Next.js, React y React-DOM
Estos son los paquetes base para que el proyecto funcione:


npm install next@latest react@latest react-dom@latest
3. Instalar Lucide React (Opcional - Para iconos)
Si decidiste usar iconos vectoriales en lugar de imágenes para la "X" o el carrito:

npm install lucide-react
🏃‍♂️ Paso 2: Ejecución del Proyecto
Una vez instalados los paquetes, puedes levantar el servidor de desarrollo:


npm run dev
Nota: La aplicación estará disponible en http://localhost:3000.

 Estructura de Carpetas Necesaria
Para que los comandos de importación funcionen, asegúrate de tener esta jerarquía:

Plaintext
teorico1/
├── components/       # Header.jsx, ProductList.jsx, Invoice.jsx
├── pages/            # index.js, _app.js
├── styles/           # globals.css (o en la raíz)
├── data.js           # Datos de productos y usuarios
└── package.json      # Configuración de paquetes
 Credenciales de Prueba (Login)
Para acceder a la tienda desde la pantalla de ingreso:

Usuario: admin

Contraseña: 123
