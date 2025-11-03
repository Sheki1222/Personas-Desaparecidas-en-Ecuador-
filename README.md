# Personas-Desaparecidas-en-Ecuador-


Datos descargados 
https://datosabiertos.gob.ec/dataset/personas-desaparecidas
<img width="691" height="160" alt="image" src="https://github.com/user-attachments/assets/96f60143-a9d2-418d-a4ec-24773a250eb3" />

Acciones realizadas para llegar al cumplimiento de la actividad

<img width="432" height="354" alt="image"  center src="https://github.com/user-attachments/assets/3b5244e1-7efa-4aac-a8e2-8dd84c0c5385" />


<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/b8cb70d5-ca22-4155-979a-2c4c9bd2fc29" />
workspace en Databricks
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/c70c2f40-5ce3-49de-a68d-82cb42c8c0da" />

<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/0eb24584-e67d-4520-9b81-5f88342c34af" />
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/776ff8b3-c0c0-4686-a441-e9eb5647cc07" />
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/29982b26-fa31-41ed-90ed-9cb49528401c" />
Ahora en entorno de notebook
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/7ba3452c-fcc6-4f65-9c5e-215abf7a508e" />

<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/1ed6633e-177e-44c3-9c31-4c284bca4bfb" />
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/bf556c6c-1f86-4ae8-8ced-75c8aa0b2ad3" />
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/e9376fd6-c116-42ac-bdad-cf23713c919b" />
Data del 2025
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/d063b7b8-8a9a-41c5-b4f3-6f56bb90bdb1" />
Data 2017 - 2024
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/4b996210-66d9-4efc-a774-14a624012c05" />
DataFrame usando PySpark dentro de tu notebook de Databricks
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/7500fb2b-8ef1-488b-ae95-cf0132e05d4e" />
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/7d83b429-f5ef-4951-8165-34c330b60ff8" />
Esto convertirá todos los 'SIN_DATO' a null y inferSchema podrá crear la columna como BIGINT
<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/6eb33aa2-c854-44c6-a07e-5c31bb6fb771" />
limpieza mínima y estandarización que pediste:
•	tipifica fechas (intenta varias columnas y formatos), crea anio, mes, year_month
•	normaliza provincia (trim + mayúsculas + eliminación básica de tildes)
•	valida/normaliza sexo a M / F / OTRO / DESCONOCIDO
•	extrae edad_num desde edad_aproximada (o rango_edad) y crea bins: 0-11, 12-17, 18-29, 30-44, 45-64, 65+, DESCONOCIDO
•	crea df_clean y vistas temporales para consultas SQL











