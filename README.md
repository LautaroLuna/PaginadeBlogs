# Proyecto Final Blog

Este proyecto es un blog desarrollado con Django como trabajo final del curso. Incluye autenticación de usuarios, gestión de perfiles, CRUD de páginas y sistema de mensajería.

## 🔧 Instalación

1. Cloná el repositorio:

```bash
git clone https://github.com/usuario/Django-Blog-Master.git
cd Django-Blog-Master

2.Activá el entorno virtual:

source env/Scripts/activate  # Windows
# o
source env/bin/activate  # Linux/Mac

3. Instalar las Dependencias

pip install -r requirements.txt

4.Aplicá las migraciones:

python manage.py migrate

5.Ejecutá el servidor:

python manage.py runserver

Funcionalidades y rutas principales
1. Inicio:
/
Página principal con bienvenida al blog.

2. About:
/about/
Información del desarrollador.

3. Registro/Login/Logout:

/accounts/signup/ – Crear cuenta nueva.

/accounts/login/ – Iniciar sesión.

/accounts/logout/ – Cerrar sesión.

4. Perfil de usuario:

/accounts/profile/ – Vista del perfil.

/profile/edit/ – Editar perfil.

/profile/avatar/ – Subir o cambiar avatar.

5. Posts (Blog):

/posts/ – Lista de todos los posts.

/posts/create/ – Crear nuevo post.

/posts/<slug>/ – Ver detalle de un post.

/posts/<slug>/update/ – Editar un post.

/posts/<slug>/delete/ – Eliminar un post.

6. Mensajes (privados):

/messages/send/ – Enviar un mensaje a otro usuario.

/messages/inbox/ – Ver mensajes recibidos.

/messages/sent/ – Ver mensajes enviados.

Notas
La base de datos no está incluida por seguridad (.gitignore).

Podés usar el admin de Django en /admin/ para gestionar todo.

Autor
Lautaro Nicolás Luna
Trabajo final del curso de Python/Django - Coderhouse
Argentina - 2025
