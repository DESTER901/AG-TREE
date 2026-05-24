Nexo Notes
Nexo Notes es una aplicación web para la gestión de notas personales, diseñada con un enfoque en la simplicidad y la seguridad de la información. El sistema permite a los usuarios organizar sus tareas y pensamientos mediante una interfaz privada protegida por autenticación.

Estado del Proyecto
Actualmente, la aplicación se encuentra en fase de desarrollo local. El acceso se realiza a través de localhost, con planes futuros de migración a un entorno de producción en la nube.

Características Técnicas
Autenticación de Usuarios: Sistema de registro e inicio de sesión seguro para la protección de datos.

Operaciones CRUD: Funcionalidad completa para crear, leer, actualizar y eliminar notas.

Atributos de Nota: Cada registro incluye un título, contenido y la fecha automática de creación o modificación.

Persistencia de Datos: Vinculación relacional entre las notas y el ID del usuario propietario.

Interfaz de Usuario: Diseño minimalista con soporte nativo para temas oscuros.

Tecnologías Utilizadas
Backend: Python / Flask.

Base de Datos: MySQL.

Frontend: Jinja2, HTML5 y CSS3.

Seguridad: Gestión de sesiones y hashing para el almacenamiento de contraseñas.

Guía de Instalación Local
Para ejecutar el proyecto en un entorno local, siga estos pasos:

Clonación del Repositorio:

Bash
git clone https://github.com/DESTER901/Nexo-Notes.git
cd Nexo-Notes
Configuración del Entorno Virtual:

Bash
python -m venv venv
source venv/Scripts/activate  # En Windows: venv\Scripts\activate
Instalación de Dependencias:

Bash
pip install -r requirements.txt
Configuración de la Base de Datos:

Inicie su servidor MySQL.

Cree un esquema llamado nexo_notes_db.

Configure las credenciales en un archivo .env tomando como referencia el archivo .env.example.

Ejecución de la Aplicación:

Bash
python app.py
Acceda a través del navegador en la dirección: http://127.0.0.1:5000
