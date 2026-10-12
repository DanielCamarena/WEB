# Bitacora 3

Nota: bitacora3.md fue creado en WEB con VS Code

## IA: llm - chatbot - agente 

Ver anotaciones en el pdf: [bitacora3.pdf](bitacoras/bitacora3/bitacora3.pdf)

## Python

- Lenguaje de programación de alto nivel 
- Orientado a objetos: clases (propiedades, ser gato) y objetos (un caso especifico, Garfield)

La instalacion se hizo con extensiones de VS Code

Elementos de Python:
- programas o script de python: archivo .py por ejemplo hola.py
- variables: enteros, flotantes, cadenas de caracteres (texto)
- estructuras lógicas
- estructuras repetitivas
- objetos complejos (estructuras de datos): listas, diccionarios, ...
- funciones: input + tarea + output
- modulos, paquetes, librerias: extensiones de Python

Entornos de Python: 
- manejar las librerias y sus las versiones
- instalador: pip 
- archivo que indique el entorno: .venv

### Jugando con Python

Usar copilot para crear y configurar el entorno de Python. 

Abrir una terminal y activar python:

cd "C:\Users\quant\Documents\WEB"
.\.venv\Scripts\Activate.ps1

probar python:

python

y te sale:

(.venv) PS C:\Users\quant\Documents\WEB> python
Python 3.12.10 (tags/v3.12.10:0cc8128, Apr  8 2025, 12:21:36) [MSC v.1943 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
Ctrl click to launch VS Code Native REPL (https://aka.ms/python-native-repl)
>>>

Ejecutando scripts:

(.venv) PS C:\Users\quant\Documents\WEB> python hola.py
¿Cómo te llamas? The Ransom
¡Hola, The Ransom!
(.venv) PS C:\Users\quant\Documents\WEB> python bitacoras\bitacora3\variables.py
Ana
25
1.68
True
(.venv) PS C:\Users\quant\Documents\WEB>


## Aplicacion web con python + streamlit 

### streamlit
servicio para ejecutar sitios web con python

https://streamlit.io/

registrarse con la cuenta de github

### Aplicacion de ejemplo

Un programa para graficar fractales

Prompt: objetivo + informacion/contexto + rol + formato de salida

Prompt 1: Quiero crear una aplicacion para graficar fractales en la carpeta proyectos\appfractal, dicha aplicacion debe poder ejecutarse con streamlit. Dame un plan para ello.

Recomendaciones y decisiones del agente de IA: 
- dividir de lo que ocupa cada script: interfaz en app.py, matemática en fractals.py 
- documentacion: README
- entorno propio: .venv dentro de la carpeta, determinado por requirements.txt
- pruebas automaticas: moralmente obligatorio
- archivo .gitignore: archivos temporales, entorno

Cómo usar la aplicacion:
cd C:\Users\quant\Documents\WEB\proyectos\appfractal
.\.venv\Scripts\Activate.ps1
streamlit run app.py


Prompt 2: Publicar en github en https://github.com/DanielCamarena/fractalia.git, y luego en streamlit web. Dame una guia paso a paso. 

Crear el repositorio público en github:
https://github.com/DanielCamarena/fractalia.git

Iniciar git en la carpeta
Hacer un commit inicial
Publicar en github 

Ir a streamlit
Create app desde repo de github
Seleccionar repo
Seleccionar app.py 


## Tarea

Publicar una app en streamlit 
- sobre algo especifico
- 24 horas de plazo 
