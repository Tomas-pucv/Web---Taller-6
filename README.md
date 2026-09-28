## Desarrollo de Taller 6 - Ing Web.

Aquí encontrarás el desarrollo repositorio solicitado para el Taller 6 de Ingenería web.


Link de repositorio: https://github.com/FranciscoPonce-PUCV/-IngenieriaWebMovil2026-Paralelo1/tree/main/Taller%206#2-instalar-express

### Features

Desarrollo con Node.js + Express (Backend).

El servidor backend permite;

1. Levantarse con npm run dev en el puerto 3000.
2. Responder con un mensaje de bienvenida en GET /.
3. Responder con un saludo personalizado en GET /saludo/:nombre.
4. Responder con todas las publicaciones en formato JSON en GET /api/posts.
5. Filtrar las publicaciones por usuario con GET /api/posts?userId=....
6. Responder con una publicación en GET /api/posts/:id (y 404 si no existe).
7. Crear una publicación con POST /api/posts (y responder 400 si faltan datos).
8. Responder 404 a las rutas que no existen.
