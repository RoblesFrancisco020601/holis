# # Documentación del Sistema - Prueba3-main

## 1. Diagrama de Arquitectura

**Estructura del Sistema:**

- **Usuario**\
  ↓ (HTTP Request)
- **Servidor Django (Prueba3)**
  - `views.py`: Gestiona las peticiones.
  - `models.py`: Define la estructura de datos (Modelo Post).
  - `forms.py`: Formulario para crear publicaciones.
  - `urls.py`: Ruta de navegación entre páginas.
    ↓
- **Base de Datos SQLite**\
  (Guarda publicaciones)

**Diagrama simplificado:**

```
[Usuario] --> [Servidor Django]
[Servidor Django] --> [Modelos (Base de Datos)]
[Servidor Django] --> [Templates HTML]
```

## 2. Diagrama de Clases

Basado en `models.py`, la clase principal es:

```
+----------------+
|     Post       |
+----------------+
| - titulo       |
| - contenido    |
| - fecha_creacion |
+----------------+
```

## 3. Manual de Usuario

### Instalación

**Requisitos Previos:**

- Python 3.8 o superior
- Pip
- Virtualenv (opcional)

**Pasos de Instalación:**

```bash
# 1. Clonar el repositorio
git clone <URL-del-repo>

# 2. Entrar al proyecto
cd Prueba3-main

# 3. Crear entorno virtual
python -m venv env

# 4. Activar entorno virtual
# Windows
env\Scripts\activate
# Linux/Mac
source env/bin/activate

# 5. Instalar dependencias
pip install django

# 6. Migrar base de datos
python manage.py migrate

# 7. Ejecutar el servidor
python manage.py runserver
```

**Acceso al sistema:**

- Crear un post: `http://127.0.0.1:8000/crear/`
- Ver posts creados: `http://127.0.0.1:8000/`

### Uso del Sistema

- Accede a `/crear/` para llenar el formulario y crear una publicación.
- El sistema guarda automáticamente la fecha de creación.
- Visualiza las publicaciones en `/`.

## 4. Resumen de Archivos Importantes

| Archivo/Directorio | Descripción                                         |
| ------------------ | --------------------------------------------------- |
| `models.py`        | Define el modelo Post                               |
| `views.py`         | Controla la lógica de crear y mostrar publicaciones |
| `forms.py`         | Define el formulario de Post                        |
| `urls.py`          | Configura las rutas del sistema                     |
| `templates/`       | Contiene las plantillas HTML                        |

---


