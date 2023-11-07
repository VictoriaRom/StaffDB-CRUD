# StaffDB-CRUD
Este proyecto es un CRUD que utiliza Python, Django y MySQL para gestionar registros de personal de una organización. Permite realizar operaciones básicas como crear, leer, actualizar y eliminar registros en una base de datos MySQL. Además, ofrece funcionalidades adicionales como la carga de datos desde un archivo Excel y la exportación de registros a archivos Excel.

## Configuración del Entorno Virtual
Podes utilizar un entorno virtual para gestionar las dependencias del proyecto. A continuación, se describen dos opciones para crear y activar un entorno virtual:

### Opción 1: Utilizar `virtualenv`

Si no tenes instalado `virtualenv`. Podes instalarlo globalmente ejecutando:

```bash
pip install virtualenv
```

Luego, crea un entorno virtual:

```bash
virtualenv env
```

Activá el entorno virtual (Windows):

```bash
env\Scripts\activate
```

Activá el entorno virtual (Mac o Linux):

```bash
source env/bin/activate
```

### Opción 2: Utilizar `venv` (solo en Python 3.X)

Creá un entorno virtual con `venv`:

```bash
python -m venv env
```

Activá el entorno virtual (Windows):

```bash
env\Scripts\activate
```

Activá el entorno virtual (Mac o Linux):

```bash
source env/bin/activate
```

## Instalación

1. Cloná este repositorio en tu máquina local:

```bash
git clone https://github.com/VictoriaRom/StaffDB-CRUD.git
```

2. Navegá al directorio del proyecto:

```bash
cd StaffDB-CRUD
```

3. Instalá las bibliotecas requeridas utilizando `pip`:

```bash
pip install -r requirements.txt
```

4. Configurá la base de datos MySQL en el archivo `settings.py`. Asegurate de especificar el nombre de la base de datos, el usuario y la contraseña correctamente.

5. Creá la base de datos MySQL en tu servidor.

6. Aplicá las migraciones para crear las tablas de la base de datos:

```bash
python manage.py makemigrations
python manage.py migrate
```

## Uso

Para ejecutar la aplicación, utilizá el siguiente comando:

```bash
python manage.py runserver
```

Esto iniciará el servidor de desarrollo y podrás acceder a la aplicación en `http://127.0.0.1:8000/` en tu navegador.

## Funcionalidades

El proyecto incluye las siguientes funcionalidades:

- Creación, lectura, actualización y eliminación de registros de personal.
- Importación de datos desde archivos Excel.
- Exportación de registros a archivos Excel.

## Capturas de Pantalla
![Captura de pantalla 1](https://github.com/VictoriaRom/StaffDB-CRUD/blob/master/media/fotos_empleados/2023-11-06_21h45_42.png)
![Captura de pantalla 2](https://github.com/VictoriaRom/StaffDB-CRUD/blob/master/media/fotos_empleados/2023-11-06_21h45_16.png)
![Captura de pantalla 3](https://github.com/VictoriaRom/StaffDB-CRUD/blob/master/media/fotos_empleados/2023-11-06_21h45_29.png)
![Captura de pantalla 4](https://github.com/VictoriaRom/StaffDB-CRUD/blob/master/media/fotos_empleados/2023-11-06_21h45_55.png)
![Captura de pantalla 5](https://github.com/VictoriaRom/StaffDB-CRUD/blob/master/media/fotos_empleados/2023-11-06_21h45_02.png)

## Tecnologías Utilizadas
- PYTHON (django)
- MYSQL
- HTML
- CSS
- JAVASCRIPT
- BOOTSTRAP

## Contacto
Si tenes alguna pregunta o sugerencia, contactame en [victoriaaromero13@gmail.com](mailto:victoriaaromero13@gmail.com).
