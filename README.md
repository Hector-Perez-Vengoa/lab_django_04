# 📚 Library Project

Este proyecto es una base para una aplicación Django, estructurada de forma moderna con una carpeta `src/`. Incluye configuración para manejo de imágenes con Pillow y está lista para ser versionada con Git y desplegada.

## 🚀 Tecnologías usadas

- Python 3
- Django
- Pillow

⚙️ Pasos para correr el proyecto

Clonar el repositorio

    git clone https://github.com/tu_usuario/library_project.git
    cd library_projec

Crear y activar el entorno virtual

Linux o Mac:

    python3 -m venv venv

En Windows:

    python -m venv venv

Linux o Mac:

    source venv/bin/activate    

En Windows:

    venv\Scripts\activate

Instalar las dependencias

    pip install -r requirements.txt

Moverse al directorio del código fuente

    cd src

Aplicar migraciones

    python manage.py makemigrations
    python manage.py migrate

Iniciar el servidor de desarrollo

    python manage.py runserver