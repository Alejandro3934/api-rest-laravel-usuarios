# API REST - Laravel (Usuarios)

Este proyecto es una API REST desarrollada en Laravel para la gestión básica de usuarios.  
Permite realizar operaciones de:

- **GET**: Obtener todos los usuarios
- **POST**: Agregar un nuevo usuario
- **PUT**: Editar un usuario existente

## 🧱 Estructura

- Base de datos: MySQL (`usuariosdb`)
- Tabla: `usuarios` (`id`, `nombre`, `email`, `timestamps`)
- Modelo: `Usuario`
- Controlador: `UsuarioController`

## 🚀 Endpoints

| Método | URL                  | Acción               |
|--------|----------------------|----------------------|
| GET    | /api/usuarios        | Listar usuarios      |
| POST   | /api/usuarios        | Agregar usuario      |
| PUT    | /api/usuarios/{id}   | Editar usuario       |

## ⚙️ Instalación

1. Clona el repositorio
2. Crea la base de datos `usuariosdb`
3. Configura el archivo `.env`
4. Ejecuta: `php artisan migrate`
5. Corre el servidor: `php artisan serve`

---

¿Quieres que te lo deje ya listo para copiar y pegar en GitHub o agregarlo dentro del ZIP también?

