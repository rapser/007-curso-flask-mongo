# Flask con MongoDB

Creamos un entorno virtual

```sh
$ pip install virtualenv
$ virtualenv venv
```

Para ejecutar el entorno virtual en MacOS usamos lo siguiente

```sh
$ source venv/bin/activate
```

Si queremos salir del entorno virtual usamos

```sh
$ deactivate
```

## Instalación de módulos

En el terminal agregamos los modulos necesarios para el proyecto

```sh
$ pip install flask pymongo
```

### Requerimientos

Podemos instalar los modulos desde un archivo requeriments de la siguiente forma

```sh
$ pip install -r requirements.txt
```

Para generar este archivo en nuestro proyecto usamos lo siguiente

```sh
$ pip freeze > requirements.txt
```

## Ejecución

Si contamos con los modulos y el entorno virtual activado, corremos el proyecto con

```sh
$ python run.py
```
