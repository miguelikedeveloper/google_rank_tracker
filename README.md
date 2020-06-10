# Google Rank Tracker!

Google Rank Tracker es un sencillo script que nos permitirá extraer los resultados de las SERPS para las Keywords seleccionadas.   

# Requerimientos

 1. Python 3

## Primeros Pasos

1. `pip install -r requirements.txt`
2. Editar el archivo **rank_tracker.py** y añadir las *KEYWORDS* que vamos a querer trackear. 
3. `python rank_tracker.py`
## Vista Previa del Programa

> Una imagen vale más que 1000 palabras

![enter image description here](https://israelperez.ninja/wp-content/uploads/2020/06/google-rank-tracker.png)
## ¿Cómo Funciona?
El programa hará una búsqueda en Google extrayendo los 100 primeros resultados, después almacenará los resultados en un CSV. 

```mermaid
graph LR
A[Keyword] -- Búsqueda en Google --> B((Extracción de resultados))
A --> C()
B --> D{Datos  CSV}
C --> D
```
**¿Simple verdad?** Pues eso es todo.
