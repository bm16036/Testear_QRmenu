##Menú Digital — Incremento Frontend

Interfaz administrativa desarrollada en Angular 17+ para la gestión de menús digitales multiempresa, conectada a un backend desarrollado en Java (Spring Boot).
Este incremento se centra en las vistas del administrador, la validación de formularios y la organización modular del panel.

##Contenido del repositorio

El repositorio contiene dos módulos principales:

men--digital-main/ → Proyecto Angular (frontend administrativo).

menu-backend-public/ → Proyecto Spring Boot (backend REST).

El foco de este incremento incluye:

Pantalla de inicio de sesión.

Panel de administración protegido.

Módulos CRUD de Empresas, Categorías, Productos y Usuarios.

Integración con servicios de conexión.

##Estructura relevante

src/
├── app/
│   ├── core/        # Modelos, servicios y guard de autenticación
│   ├── features/    # Componentes de login y módulos administrativos
│   └── styles/      # Estilos compartidos para las pantallas de gestión
└── environments/    # Configuración (API base y uso de mocks)

##Datos de acceso

Credenciales de prueba:

Correo: admin@resto.test

Contraseña: admin123

Empresa: Mi Restaurante

##Descripción general

El sistema permite al administrador:

Iniciar sesión y acceder al panel.

Gestionar Empresas: RUC, razón social, logo y contactos.

Gestionar Categorías: nombre y estado activo/inactivo.

Gestionar Productos: código, nombre, descripción, precio y categoría.

Gestionar Usuarios: nombre, rol y empresa asociada.

##Requisitos

Node.js: 20 o superior

npm: 10 o superior

Angular CLI: 17+

Docker Desktop

##Ejecución rápida

docker compose up --build


##El servidor de Angular se iniciará en
http://localhost:4200

