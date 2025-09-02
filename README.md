# Material per l'assignatura de: Introducció a Python per a economistes
## Tallers transversals de la FEE

Curso: Introducción a Python para economistas
Créditos/horas: 1 crédito genérico (Total 25h, donde 10h son clases presenciales, 15h
trabajo del alumnado)
Periodo de impartición: 5 viernes lectivos consecutivos
Idioma de impartición: castellano y catalán
N.º máximo de alumnos: 25

Més informació a: https://fee.uib.cat/w/tallers-transversals-de-la-fee

## Organización del Código

### Estructura del Proyecto

```
TallerPythonFEE/
├── README.md                 # Documentación principal del proyecto
├── requirements.txt          # Dependencias de Python
├── conf.py                  # Configuración del proyecto
├── index.rst                # Índice para documentación
├── Makefile                 # Scripts de automatización
├── make.bat                 # Scripts de automatización para Windows
├── LICENSE                  # Licencia del proyecto
│
├── data/                    # Datos y archivos de entrada
│   ├── data_groups_cursos.csv
│   ├── data_groups.csv
│   ├── municipis.csv
│   ├── presupuesto_gastos_2023.csv
│   ├── presupuesto_ingresos_2023.csv
│   ├── rdu-weather-history.csv
│   ├── ResultadosElectorales2022.csv
│   ├── Speculation_Watch_List.csv
│   ├── tin00171_linear.csv.gz
│   ├── WHO.csv
│   └── fitxers_Data_4Sessio.zip
│
├── notebooks/               # Jupyter notebooks de aprendizaje
│   ├── 1_PythonIntroduccio.ipynb      # Introducción a Python
│   ├── 2_PandasIntroduccio.ipynb      # Introducción a Pandas
│   ├── 3_Pandas_Seleccio.ipynb        # Selección de datos en Pandas
│   ├── 4_Pandas_Modificacio.ipynb     # Modificación de datos en Pandas
│   ├── 5_PandasGroups.ipynb           # Agrupación de datos en Pandas
│   └── 6_PandasVisualitzacions.ipynb  # Visualizaciones con Pandas
│
└── homework/                # Actividades y tareas del alumno
    ├── activitat_1_1.ipynb  # Actividad 1.1
    ├── activitat_1_2.ipynb  # Actividad 1.2
    ├── activitat_4.ipynb    # Actividad 4
    └── activitat_5.ipynb    # Actividad 5

```

### Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal
- **Jupyter Notebooks**: Entorno de desarrollo interactivo
- **Pandas**: Manipulación y análisis de datos
- **Matplotlib/Seaborn**: Visualización de datos
- **NumPy**: Computación numérica

### Configuración del Entorno

El proyecto está diseñado para ser utilizado en Google Colab.

Para configurar un entorno propio de desarrollo:
1. Instalar las dependencias: `pip install -r requirements.txt`
2. Ejecutar Jupyter: `jupyter notebook`
3. Navegar a la carpeta correspondiente según la sesión

