# Nexo Notes

Nexo Notes es una aplicación web para la gestión de notas personales, diseñada con un enfoque en la simplicidad y la seguridad de la información. El sistema permite a los usuarios organizar sus tareas y pensamientos mediante una interfaz privada protegida por autenticación.

## Estado del Proyecto
Actualmente, la aplicación se encuentra en fase de desarrollo local. El acceso se realiza a través de localhost, con planes futuros de migración a un entorno de producción en la nube.

## Características Técnicas
* **Autenticación de Usuarios:** Sistema de registro e inicio de sesión seguro para la protección de datos.
* **Operaciones CRUD:** Funcionalidad completa para crear, leer, actualizar y eliminar notas.
* **Atributos de Nota:** Cada registro incluye un título, contenido y la fecha automática de creación o modificación.
* **Persistencia de Datos:** Vinculación relacional entre las notas y el ID del usuario propietario.
* **Interfaz de Usuario:** Diseño minimalista mediante JavaScript.

## Tecnologías Utilizadas
* **Backend:** Python / Flask (Manejo de rutas y lógica de servidor).
* **Base de Datos:** MySQL.
* **Frontend:** HTML5, CSS3 y JavaScript (Manipulación del DOM y peticiones).
* **Seguridad:** Gestión de sesiones y hashing para el almacenamiento de contraseñas.

## Guía de Instalación Local

Para ejecutar el proyecto en un entorno local, siga estos pasos:

### 1. Clonación del Repositorio
```bash
git clone [https://github.com/DESTER901/Nexo-Notes.git](https://github.com/DESTER901/Nexo-Notes.git)
cd Nexo-Notes
