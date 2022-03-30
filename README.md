# Ejemplo de examen POO
Este es un ejemplo de como será el examen de POO, usando python y evaluado con pytest

### El ejercicio
Desarrolle una clase llamada PruebaExamen, dentro del archivo PruebaExamen.py
debe tener los siguientes atributos

+nombre
-apellido

y los siguientes métodos

__init__ que recibe nombre y apellido como parámetros 

getApellido que retorna el apellido

__str__ que retorna el nombre completo concatenado

### Setup command
`sudo -H pip3 install pytest`

### Run command
`pytest`

### Notes
- pip's install path is not included in the PATH var by default, so without installing via `sudo -H`, pytest would be unaccessible.
