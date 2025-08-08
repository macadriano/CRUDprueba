# CRUD de Usuarios - Aplicación Web

Una aplicación web completa para gestionar usuarios con operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

## 🚀 Características

- ✅ **Crear usuarios** - Agregar nuevos usuarios con nombre, email y edad
- 📖 **Listar usuarios** - Ver todos los usuarios registrados en tarjetas elegantes
- ✏️ **Editar usuarios** - Modificar información de usuarios existentes
- 🗑️ **Eliminar usuarios** - Remover usuarios con confirmación
- 📱 **Diseño responsivo** - Funciona perfectamente en móviles y escritorio
- 🎨 **Interfaz moderna** - UI atractiva con gradientes y animaciones
- ⚡ **Tiempo real** - Actualizaciones instantáneas sin recargar página

## 🛠️ Tecnologías Utilizadas

### Backend
- **Flask** - Framework web de Python
- **SQLite** - Base de datos ligera
- **Flask-CORS** - Manejo de CORS para API

### Frontend
- **HTML5** - Estructura
- **CSS3** - Estilos modernos con gradientes y animaciones
- **JavaScript ES6+** - Lógica del frontend y llamadas a API

## 📦 Instalación y Uso

### 1. Instalar dependencias
```bash
pip install -r requirements.txt
```

### 2. Ejecutar la aplicación
```bash
python app.py
```

### 3. Abrir en el navegador
Visita: `http://localhost:5000`

## 📋 API Endpoints

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET | `/api/users` | Obtener todos los usuarios |
| POST | `/api/users` | Crear un nuevo usuario |
| GET | `/api/users/{id}` | Obtener un usuario específico |
| PUT | `/api/users/{id}` | Actualizar un usuario |
| DELETE | `/api/users/{id}` | Eliminar un usuario |

### Ejemplo de datos de usuario:
```json
{
  "name": "Juan Pérez",
  "email": "juan@email.com",
  "age": 30
}
```

## 🗄️ Estructura de la Base de Datos

### Tabla: users
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | INTEGER | ID único (auto-incremento) |
| name | TEXT | Nombre completo (requerido) |
| email | TEXT | Email único (requerido) |
| age | INTEGER | Edad (opcional) |
| created_at | TIMESTAMP | Fecha de creación |

## 🎯 Funcionalidades

### Crear Usuario
- Formulario con validación
- Campos: nombre, email, edad
- Validación de email único
- Mensajes de éxito/error

### Listar Usuarios
- Vista en tarjetas responsivas
- Información completa de cada usuario
- Fecha de creación formateada
- Botones de acción por usuario

### Editar Usuario
- Carga datos en el formulario
- Actualización en tiempo real
- Validación de datos
- Opción de cancelar edición

### Eliminar Usuario
- Confirmación antes de eliminar
- Eliminación inmediata de la vista
- Mensajes de confirmación

## 🎨 Características de Diseño

- **Gradientes modernos** - Colores atractivos
- **Animaciones suaves** - Hover effects y transiciones
- **Diseño responsivo** - Adaptable a cualquier pantalla
- **Iconos emoji** - Interfaz amigable y moderna
- **Alertas elegantes** - Notificaciones de estado
- **Loading states** - Indicadores de carga

## 🔧 Personalización

### Cambiar colores
Modifica las variables CSS en `templates/index.html`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Agregar campos
1. Actualiza la tabla en `app.py`
2. Modifica el formulario HTML
3. Actualiza las funciones JavaScript

## 📱 Compatibilidad

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Móviles (iOS/Android)

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia MIT.