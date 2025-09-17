# Introduccion a Python

Version de repositorio: 0.0.0

Bienvenido al Workbook de Itroducción a Python. En este Workbook aprenderás los conceptos básicos de programación utilizando el lenguaje Python. Está diseñado para principiantes y no tiene como requisito ninguna experiencia previa en programación ni ninguna otra habilidad técnica.
El objetivo es que al finalizar el Workbook tengas una comprensión sólida de los fundamentos de Python y puedas comenzar a escribir tus propios programas basicos.

# Estructura del Workbook

## Contenidos:
A lo largo de este Workbook, cubriremos los siguientes temas:
1. Primeros pasos en programación
2. Sintaxis básica de Python
3. Variables y tipos de datos
4. Estructuras de control de flujo
5. Listas y strings
6. Funciones y módulos
7. Listas de listas
8. Recursion
9. Archivos
10. Programación orientada a objetos simple
11. Ordenacion y busqueda

## Organización:
El Workbook tendra la siguiente estructura de carpetas.
- Los contenidos de cada capitulo estaran en la carpeta `contenidos/`, donde cada subcarpeta corresponde a un tema del Workbook, teniendo los materiales de los topicos y los ejercicios asignados a sus correspondientes materiales.
- Las tareas se encontraran en la carpeta `tareas/`, donde cada subcarpeta tendra el respectivo enunciado y hoja de respuestas.

```
Introduccion a Programacion en Python/
│
├── contenidos/
|   ├── 01_primeros_pasos/
|       ├── capitulo_01_1.ipynb        # Python y la Programación
|       ├── capitulo_01_2.ipynb        # Primeros pasos en programación (Python en Google Colab)
|       ├── ejercicios_01_1.ipynb
|       ├── content/
|
|   ├── 02_sintaxis_basica/
|       ├── capitulo_02_1.ipynb        # Funciones internas y sintaxis básica de Python
|       ├── capitulo_02_2.ipynb        # Funcionamiento del lenguaje de programación Python
|       ├── ejercicios_02_1.ipynb
|       ├── content/
|
|   ├── 03_variables_datos/
|       ├── capitulo_03_1.ipynb        # Variables y tipos de datos
|       ├── capitulo_03_2.ipynb        # Operadores y expresiones
|       ├── capitulo_03_3.ipynb        # Conversión de tipos
|       ├── capitulo_03_4.ipynb        # Entrada y salida de datos
|       ├── ejercicios_03_1.ipynb
|       ├── content/
|
|   ├── 04_control_de_flujo/
|       ├── capitulo_04_1.ipynb        # Estructuras de control de flujo
|       ├── capitulo_04_2.ipynb        # Condicionales
|       ├── capitulo_04_3.ipynb        # Bucles
|       ├── capitulo_04_4.ipynb        # Manejo de excepciones
|       ├── ejercicios_04_1.ipynb
|       ├── content/
|
|   ├── 05_listas_y_strings/
|       ├── capitulo_05_1.ipynb        # Listas
|       ├── capitulo_05_2.ipynb        # Métodos de listas
|       ├── capitulo_05_3.ipynb        # Strings
|       ├── capitulo_05_4.ipynb        # Métodos de strings
|       ├── ejercicios_05_1.ipynb
|       ├── content/
|
|   ├── 06_funciones_y_modulos/
|       ├── capitulo_06_1.ipynb        # Funciones
|       ├── capitulo_06_2.ipynb        # Módulos y paquetes
|       ├── capitulo_06_3.ipynb        # Alcance de variables
|       ├── ejercicios_06_1.ipynb
|       ├── content/
|
|   ├── 07_listas_de_listas/
|       ├── capitulo_07_1.ipynb        # Listas de listas
|       ├── capitulo_07_2.ipynb        # Comprensión de listas
|       ├── ejercicios_07_1.ipynb
|       ├── content/
|
|   ├── 08_recursion/
|       ├── capitulo_08_1.ipynb        # Funciones recursivas
|       ├── ejercicios_08_1.ipynb
|       ├── content/
|
|   ├── 9_archivos/
|       ├── capitulo_09_1.ipynb        # Manejo de archivos de texto
|       ├── capitulo_09_2.ipynb        # Escritura de archivos
|       ├── capitulo_09_3.ipynb        # Archivos CSV
|       ├── capitulo_09_4.ipynb        # Archivos JSON
|       ├── ejercicios_09_1.ipynb
|       ├── content/
|
|   ├── 10_programacion_orientada_a_objetos/
|       ├── capitulo_10_1.ipynb        # Introducción a la programación orientada a objetos
|       ├── capitulo_10_2.ipynb        # Materiales y objetos
|       ├── capitulo_10_3.ipynb        # Atributos y métodos
|       ├── ejercicios_10_1.ipynb
|       ├── content/
|
|   └── 11_ordenacion_y_busqueda/
|       ├── capitulo_11_1.ipynb        # Sort
|       ├── capitulo_11_2.ipynb        # Búsqueda
|       ├── capitulo_11_3.ipynb        # Algoritmos de ordenación
|       ├── ejercicios_11_1.ipynb
|       ├── content/
|
├── tareas/
|   ├── t_0/
|       ├── t_0_Hoja_Respuestas.ipynb
|       ├── t_0_Instrucciones.ipynb
|   ├── t_1/
|       ├── t_1_Hoja_Respuestas.ipynb
|       ├── t_1_Instrucciones.ipynb
|   ├── t_2/
|       ├── t_2_Hoja_Respuestas.ipynb
|       ├── t_2_Instrucciones.ipynb
├── miscelaneos/
|   ├── reWorkbooks_adicionales/
|   ├── glosario.md
└── README.md
```

## Como Empezar
Al querer aprender a progrmamar, puede parecer aterrador tener que aprender un nuevo lenguaje, instalar cosas, y trabajar con un nuevo entorno. Sin embargo, al ser un Workbook introductorio, no te sera necesario instalar nada, ya que utilizaremos un espacio para programar llamado [**Google Colab**](https://colab.research.google.com/). Este espacio te permitira ejecutar código Python directamente en tu navegador sin necesidad de instalar nada en tu computadora. Asi podras aprender lo basico y necesario, acostumbrate a escribir, y sobre todo poder tener acceso de una forma mas amistosa.

Para comenzar, simplemente abre la carpeta del Workbook en [**Google Drive**](https://drive.google.com/) en *Mi Unidad*.

### Acceder a los materiales en Google Drive
1. Abre el enlace de Google Drive y dirigete en *Mi Unidad* selecciona la carpeta `Python-Programming` y podrás encontrar la carpeta `Python_Introductorio`.

<img src="contenidos\c01_Primeros_Pasos\content\dr_miunidad.png" alt="menu" width="400">

2. Selecciona la carpeta `contenidos/`.

<img src="contenidos\c01_Primeros_Pasos\content\dr_pyintro.png" alt="menu" width="400">

3. Selecciona la carpeta del contenido que quieras estudiar: `c01_Primeros_Pasos/`.

<img src="contenidos\c01_Primeros_Pasos\content\dr_contenidos.png" alt="menu" width="400">

4. Selecciona la carpeta del capitulo que deseas revisar: `capitulo_01_1.ipynb`.

<img src="contenidos\c01_Primeros_Pasos\content\dr_clases.png" alt="menu" width="400">

5. Y listo! Ahora puedes comenzar a estudiar sin problemas. Cada capitulo contiene explicaciones, ejemplos de código y ejercicios prácticos para que puedas practicar lo aprendido.

<img src="contenidos\c01_Primeros_Pasos\content\dr_collab.png" alt="menu" width="1000">


### Recursos Adicionales
A lo largo del Workbook, se proporcionarán Recursos Adicionales, como enlaces a documentación oficial, tutoriales en línea y ejercicios prácticos para reforzar tu aprendizaje. Estos estarán disponibles en la carpeta `miscelaneos/recursos_adicionales/`. Puedes ver el listado en `miscelaneos/glosario.md`.

### Contacto
Si tienes alguna pregunta o necesitas ayuda, no dudes en contactarme a través de [anatomik2025@gmail.com](mailto:anatomik2025@gmail.com).