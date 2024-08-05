# Para le presente trabajo consistente en:

Desarrollar un script en Python que permita realizar operaciones de análisis de datos
avanzados utilizando numpy y pandas, extrayendo información de una base de datos
MySQL, y visualizando los resultados con matplotlib.

## Requerimientos

### Estructura del Proyecto:
● Crear un repositorio en GitHub llamado "advanced-data-analysis".
● Un archivo inicial que se llame “main.py”
Base de Datos:
● Crear una base de datos MySQL llamada “CompanyData”.
● Crear una tabla llamada “EmployeePerformance” con las siguientes columnas:
id (Clave primaria autoincremental)
employee_id (Números enteros)
department (Textos)
performance_score (Números con decimales)
years_with_company (Números enteros)
salary (Números con decimales)
Poblar la tabla con 1000 registros de datos ficticios.
>> Se recomienda usar Mockaroo para la población de los datos.

### Análisis de Datos:
● Utilizar pandas para extraer los datos de la tabla EmployeePerformance.
● Calcular las siguientes estadísticas para cada departamento:
● Media, mediana y desviación estándar del performance_score.
● Media, mediana y desviación estándar del salary.
● Número total de empleados por departamento.
● Correlación entre years_with_company y performance_score.
● Correlación entre salary y performance_score.

### Visualización de Datos:
● Utilizar matplotlib para crear las siguientes visualizaciones:
● Histograma del performance_score para cada departamento.
● Gráfico de dispersión de years_with_company vs. performance_score.
● Gráfico de dispersión de salary vs. performance_score.

### Inicio:

Se ha creado un entorno de trabajo virtual con el comando:
```bash
python -m venv env
```

Se ha activado el entorno de trabajo virtual con el comando:
```bash
source env/Scripts/activate
```

Se han instalado las librerías necesarias con el comando:
```bash
pip install pandas numpy matplotlib mysql-connector-python
```

Se ha creado el archivo "main.py" con el código necesario para realizar el análisis de datos avanzados.

## Ejecución del trabajo:
La libreria sqlalchemy se ha utilizado para la conexión con la base de datos MySQL, en la cual 
se ha creado primeramente una base de datos llamada "CompanyData" y una tabla llamada "EmployeePerformance", creandose en ella 1000 registros de datos ficticios.
Para ello se utilizó la Mockaroo https://www.mockaroo.com/.
Con el archivo creado en formato csv se importó en la base de datos MySQL.
Una vez obtenido los datos, se procedió a realizar el análisis de datos avanzados, obteniendo las estadísticas solicitadas y las visualizaciones correspondientes.

La librería pandas se ha utilizado para la extracción de los datos de la tabla EmployeePerformance.

La librería matplotlib se ha utilizado para la visualización de los datos, obteniendo los gráficos solicitados.

