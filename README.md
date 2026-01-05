# MenuRes – Sistema de pedidos online para restaurantes

MenuRes es un proyecto de **Trabajo de Fin de Grado (TFG)** desarrollado para el ciclo de **Desarrollo de Aplicaciones Web (DAW)**, enfocado en la creación de un sistema de pedidos online para restaurantes con panel de administración.

El objetivo principal del proyecto es **digitalizar y optimizar el proceso de pedidos**, mejorando la experiencia del cliente y la eficiencia operativa de los establecimientos gastronómicos.

## 📚 Contexto académico

- **Ciclo**: Desarrollo de Aplicaciones Web (DAW)
- **Centro**: Formación Profesional
- **Curso**: 3º año (Doble titulación DAW + DAM)
- **Tipo de proyecto**: Trabajo de Fin de Grado (TFG)
- **Año**: 2024
- **Modalidad**: Proyecto en equipo (2 personas)

### 👥 Autores
- Alessandro Rodríguez Rojas  
- Josué Sevillano Vázquez  

## 🧩 Descripción general

MenuRes permite a los clientes:
- Navegar por restaurantes disponibles
- Visualizar productos y precios
- Añadir productos al carrito
- Realizar pedidos de forma autónoma
- Simular un proceso de pago online
- Recibir confirmación del pedido

Además, incluye un **panel de administración** exclusivo para restaurantes, desde el cual se pueden:
- Gestionar productos
- Editar o eliminar productos
- Visualizar pedidos realizados
- Mantener actualizado el catálogo

## ⚙️ Tecnologías utilizadas

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript (jQuery)

### Backend
- C#  
- .NET Framework

### Base de datos
- MySQL

### Herramientas
- Visual Studio 2022
- XAMPP / MySQL Workbench
- Azure App Service (despliegue)

## 🧱 Arquitectura

El sistema sigue una **arquitectura cliente-servidor**, separando claramente:

- **Cliente (Frontend)**: Interfaz de usuario accesible desde navegador web.
- **Servidor (Backend)**: Lógica de negocio, validaciones y comunicación con la base de datos.
- **Base de datos**: Almacenamiento estructurado de restaurantes, productos, pedidos y administradores.

Esta separación mejora la mantenibilidad, escalabilidad y seguridad del sistema.

## 🔐 Seguridad

- Acceso al panel de administración restringido
- Usuarios administradores creados manualmente por los desarrolladores
- Validaciones de formularios
- Control de datos en servidor
- Proyecto con enfoque en futuras mejoras de cifrado y control de accesos

## 🛠 Funcionalidades principales

### Cliente
- Visualización de restaurantes
- Catálogo de productos
- Carrito de compra
- Confirmación de pedido
- Redirección automática tras el pago

### Panel de administración
- Selección de restaurante
- Agregar productos
- Editar productos
- Eliminar productos
- Visualizar pedidos realizados
- Control del total de pedidos

## 🗄 Base de datos

El sistema utiliza un modelo relacional con las siguientes tablas principales:

- Restaurante
- Producto
- Pedido
- Pedidos_Productos
- Admin

Relaciones bien definidas para garantizar integridad y coherencia de datos.

## 🚀 Despliegue

La aplicación fue desplegada en **Microsoft Azure**, utilizando:
- Azure App Service
- Publicación directa desde Visual Studio

Este enfoque permitió:
- Alta disponibilidad
- Escalabilidad
- Actualizaciones rápidas del proyecto

## 📈 Aprendizajes y competencias demostradas

Este proyecto demuestra:
- Desarrollo full-stack
- Trabajo en equipo
- Organización de proyectos grandes
- Uso de bases de datos relacionales
- Arquitectura web real
- Iniciativa y autonomía
- Capacidad para llevar un proyecto de principio a fin

## 🔮 Posibles mejoras futuras

- Gestión de usuarios con roles (admin, gerente, empleado)
- Sistema de autenticación más avanzado
- Encriptación de contraseñas
- Personalización de pedidos
- Promociones y cupones
- Analítica y estadísticas de pedidos
- Sistema de fidelización de clientes

## 📄 Estado del proyecto

✅ Proyecto finalizado  
📌 Uso académico  
🛠 No en producción actualmente
