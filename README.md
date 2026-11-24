
# Blog Django

Proyecto base de un blog web desarrollado con Django.

## Descripción

- Proyecto principal blog_project.
- Aplicación posts.
- Templates HTML con herencia.
- Estilos CSS.

## Requisitos

- Python
- Django

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/cgarcia9091/entrega8.git
```

Ingresar a la carpeta:

```bash
cd entrega8
```

Crear el entorno virtual:

```bash
python -m venv venv
```

Activar el entorno virtual en Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

Aplicar las migraciones:

```bash
python manage.py migrate
```

Ejecutar el servidor:

```bash
python manage.py runserver
```

Abrir en el navegador:

http://127.0.0.1:8000/

## Aplicaciones

- `posts`: aplicación inicial destinada a gestionar las publicaciones del blog.

## Configuración

- Idioma: español de Argentina (`es-ar`).
- Zona horaria: `America/Argentina/Buenos_Aires`.
