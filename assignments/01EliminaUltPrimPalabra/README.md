![Tec de Monterrey](../../images/logotecmty.png)
# Elimina Primera y Ultima Palabra
Archivos-Elimina Primera y Ultima Palabra


Modifica el programa que se encuentra en la carpeta `src` que se llama `exercise.py` y que contiene el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario, el programa la va a ignorar al ejecutarse.

Lee del archivo "Data.txt" cada una de sus líneas. Añade una función llamada "cortar_linea" que reciba cada una de las líneas leídas del archivo (una por una), y regrese otra línea eliminando la primera y la última palabra.

El programa debe tomar cada línea del archivo, llamar a la función para eliminar la primera y última palabra de cada línea, y luego colocar esa línea en un nuevo archivo de salida llamado "nuevasFrases.txt".

Entrada
Este programa toma la entrada del archivo Data.txt

Salida
Este programa genera la salida en un archivo llamado nuevasFrases.txt

<b>Ejemplo de archivo de entrada:</b>
```
Tres tristes tigres,
tragaban trigo en un trigal,
en tres tristes trastos
tragaban trigo tres tristes tigres.
```

<b>Ejemplo de archivo de salida: </b>
```
tristes
trigo en un
tres tristes
trigo tres tristes
```

**Nota:** No te preocupes por esta parte del código `if __name__ == '__main__':` por el momento. No la vamos a necesitar para este programa, pero es una buena práctica incluirla y quedará más claro para que sirve en los siguientes ejercicios.

Una vez que termines tu actividad y la hayas probado con `pytest`, subela a tu repositorio en GitHub, con el proceso de commit + push.
