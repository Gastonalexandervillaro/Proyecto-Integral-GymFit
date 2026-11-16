# 🏋️‍♂️ GymFit — Sistema Integral de Gestión de Gimnasios

Plataforma web **Full-Stack** desarrollada en **Java & Spring Boot** para la administración integral de gimnasios. El sistema centraliza la gestión de socios, control de acceso mediante códigos QR, tienda de productos, planificación de rutinas de entrenamiento y seguimiento nutricional en una interfaz moderna y responsiva.

---

## 🎯 Objetivo del Proyecto

Digitalizar y automatizar la operatoria diaria de un gimnasio, brindando herramientas diferenciadas tanto para los administradores del establecimiento como para los socios (acceso rápido, visualización de rutinas personalizadas y planes alimentarios).

---

## 🚀 Funcionalidades Principales

- **Autenticación y Seguridad por Roles**: Registro de usuarios, inicio de sesión con perfiles diferenciados (Administrador / Socio) y flujo de recuperación de contraseña por correo electrónico.
- **Control de Acceso con Códigos QR**: Generación dinámica de credenciales QR para validación rápida de socios e ingreso al establecimiento.
- **Panel de Administración**: Gestión centralizada de usuarios, membresías activas, catálogo de productos e inventario.
- **Módulo de Rutinas y Ejercicios**: Creación, asignación y visualización de planes de entrenamiento estructurados por día (`RoutineController`, `RoutineService`, carga inicial automatizada).
- **Módulo de Nutrición y Dietas**: Administración y seguimiento de planes alimentarios y comidas (`DietController`, `DietService`).
- **Tienda y Catálogo de Productos (`ProductController`)**: Gestión de suplementos y artículos deportivos con soporte de imágenes y control de stock.

---

## 🛠️ Stack Tecnológico

- **Backend**: Java 17, Spring Boot, Spring Data JPA, Hibernate, Maven
- **Frontend**: HTML5, CSS3, JavaScript, Thymeleaf
- **Base de Datos**: MySQL (modelado relacional productivo) y H2 Database (base integrada para ejecución inmediata y pruebas locales)
- **DevOps / Despliegue**: Docker (`docker-compose.yml`)

---

## ⚙️ Instalación y Ejecución Local

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/Gastonalexandervillaro/Proyecto-Integral-GymFit.git](https://github.com/Gastonalexandervillaro/Proyecto-Integral-GymFit.git)
