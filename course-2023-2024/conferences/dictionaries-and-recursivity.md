# Diccionarios y Recursividad

## Diccionarios

### Uso de los diccionarios

- Creación de diccionarios vacíos

```python
d = {}
d = dict()
```

- Creación de diccionarios con datos

```python
d = {'a': 1, 'b': 2, 'c': 3}
d = dict(a=1, b=2, c=3)
d = dict([['a', 1], ['b', 2], ['c', 3]])
d = dict([('a', 1), ('b', 2), ('c', 3)])
```

- Acceso a los datos

```python
d['a']  # Si no existe, KeyError
d.get('a')  # Si no existe, None
d.get('a', 0)  # Si no existe, 0
```

- Modificación de los datos

```python
d['a'] = 1  # Si no existe, lo crea, si existe, lo modifica
d.setdefault('a', 1)  # Si no existe, lo crea, si existe, no lo modifica
d.update({'a': 1, 'b': 2, 'd': 4})  # Actualiza los datos y crea los que no existen
```

- Eliminación de datos

```python
del d['a']  # Si no existe, KeyError
d.pop('a')  # Si no existe, KeyError, devuelve el valor eliminado
d.pop('a', 0)  # Si no existe, 0, devuelve el valor eliminado
d.popitem()  # Elimina el último elemento agregado, devuelve la clave y el valor eliminados
d.clear()  # Elimina todos los elementos
```

- Operaciones con diccionarios

```python
len(d)  # Número de elementos
'a' in d  # True si existe la clave 'a'
'a' not in d  # True si no existe la clave 'a'
d.keys()  # Devuelve las claves
d.values()  # Devuelve los valores
d.items()  # Devuelve los pares clave-valor
d.copy()  # Devuelve una copia del diccionario (shallow copy)
```

- Iteración sobre diccionarios

```python
for k in d:  # Itera sobre las claves
    print(k, d[k])

for k, v in d.items():  # Itera sobre los pares clave-valor
    print(k, v)
```

### Utilidad de los diccionarios

- Conteo de palabras utilizando listas vs diccionarios
- De forma general:
  - Asociación clave-valor
  - Búsqueda eficiente
  - Claves no numéricas
  - Datos dispersos

## Recursividad

### Definición

- Una función se llama recursiva si se llama a sí misma
- Una solución recursiva es aquella que se basa en la recursividad:
    1. Casos bases
    2. Reducción del problema
    3. Llamadas recursivas
    4. Combinación de los resultados

### Ejemplos

- Factorial
- Fibonacci
- Busqueda binaría
- Ordenamiento por mezcla
- Ocho reinas

> JSON - Combinación de diccionarios y recursividad
