# Project FlaskyBlog

Proyecto creado en Python haciendo uso del framework Flask en el que se tiene un blog \
para la volcadura de informacion importante que se requiera; se hace uso de render templates \
con Jinja; asimismo, se integra persistenica a traves de SQLite. Se ultiman detalles con la \
autenticacion y autorizacion de usuarios con roles y permisos determinados.

## Requisitos previos

- Python 3.x
- pip

## Instrucciones de instalacion

1. Clona el repositorio:
```bash
git clone git@github.com:ZALOFARG/FlaskyBlog.git
```

2. Navega al directorio del proyecto:
```bash
cd FlaskyBlog/
```

3. Crea y activa un entorno virtual (opcional):
```bash
python3 -m venv venv
source venv/bin/activate
# En windows usa `venv\Scripts\activate`
```

4. Instala las dependencias:
```bash
pip install -r requirements.txt
```

5. Ejecuta la aplicacion:
```bash
flask --app microblog run
```
