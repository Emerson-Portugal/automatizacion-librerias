# Automatiacion de Librerias

Se va a dividir en tres pasos

- El primer paso sera general el "requirements.txt"
- El segundo paso sera instalar el "requirements.txt"
- Opcional sera crear el entorno virtual 

---

### Requisitos 
- python
- virtualenv
> Instalar virtualenv
```
pip install virtualenv
```
----

Si queremos ver las librerias que tenemos instaladas para usar nuestro proyecto

```python
pip list
```

## Paso 1

> En este paso para a crear el archivo "requirements.txt", donde estara todo nuestras librerias, para que nustro proyecto funcione en otras maquinas 

```python
pip freeze > "requirements.txt"
```

## Paso 2

> Una ver generado el archivo "requirements.txt" y nos encontramos en otra maquina, vamos instalar las librerias para nuestro proyecto

```python
pip install -r ".\requirements.txt"
```


## Opcional

Si queremos crear un entorno virtual con python, para no tener problemas con las librerias y tener un monton de librerias instalas en tu PC, te recomiendo un entorno virtual


>creamos el entorno virtual
```
python -m virtualenv venv
```

> Ejecutamos virtualenv
```python
.\venv\Scripts\activate
```

> Detemos virtualenv
```python
deactivate
```


