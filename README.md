# PEC03-01-25
proyecto que conecta django con una base de datos externa (postgresql o mysql)

# Gestión de Cursos

Este proyecto es una aplicación web de gestión de cursos desarrollada con Django. Permite crear, visualizar y gestionar cursos.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Contribuir](#contribuir)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu_usuario/gestion_cursos.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd gestion_cursos
    ```
3. Crea y activa un entorno virtual:
    ```bash
    python -m venv env
    source env/bin/activate  # En Windows: env\Scripts\activate
    ```
4. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```
5. Configura el archivo `.env` con tus variables de entorno.

6. Realiza las migraciones de la base de datos:
    ```bash
    python manage.py migrate
    ```

## Uso

1. Inicia el servidor de desarrollo:
    ```bash
    python manage.py runserver
    ```
2. Abre tu navegador y navega a `http://127.0.0.1:8000/` para ver tu aplicación en funcionamiento.

## Características

- Crear nuevos cursos.
- Visualizar la lista de cursos.
- Editar y eliminar cursos.

## Tecnologías Utilizadas

- [Django](https://www.djangoproject.com/)
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [PostgreSQL](https://www.postgresql.org/)

## Contribuir

Si deseas contribuir, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una rama (`git checkout -b feature-nueva`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva característica'`).
4. Envía tus cambios al repositorio (`git push origin feature-nueva`).
5. Crea un nuevo Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

## Contacto

Tu Nombre - [tu_email@example.com](mailto:tu_email@example.com)

Proyecto Link: [https://github.com/tu_usuario/gestion_cursos](https://github.com/tu_usuario/gestion_cursos)
