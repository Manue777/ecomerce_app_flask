## Crear un entorno virtual

```
python -m venv venv
```

## Activar el entorno virtual

```
venv\Scripts\activate
source venv/Scripts/activate
source venv/bin/activate
```

## Instalar Flask

```
pip install flask
```

## Correr la aplicación de flask

```
flask --debug run
```

## Instalar sqlalchemy

```
pip install Flask-SQLAlchemy
```

## Registrar las dependencias que estamos usando

```
pip freeze > requirements.txt
```

## Migrar la base de datos

```
pip install Flask-Migrate
flask db init
flask db migrate -m "first migration"
flask db upgrade
```

## Instalar Flask Cors

```
pip install flask-cors
```

## Para correr el frontend

```
npm install
npm run dev
```