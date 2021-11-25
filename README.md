# Lenguaje y herramientas
R y R Studio. Reportado con RMarkdown.

# IRA
Análisis de "Casos de infecciones respiratorias agudas en territorio argentino, por localidad, desde 2018 hasta primer trimestre de 2021".  Obtenidos de https://datos.gob.ar/

### Seleccion de datos

¿Como se obtuvieron los datos?\
Se obtuvieron de la pagina del gobierno de Argentina, https://datos.gob.ar/, que engloba set de datos obtenidos mediante diferentes estudios y metodos. En su gran mayoria corresponden a proyectos de analítica y/o censado estatales.\
Nuestro dataset forma parte del paquete de datos relacionados a estudios sanitarios y epidemicos denominado "Área de Salud". Específicamente corresponden al tipo secundario e incluyen información sobre "Casos de infecciones respiratorias agudas en territorio argentino, por localidad, desde 2018 hasta primer trimestre de 2021". Para ello, se extraen y mergean dos dataset que incluyen informacion de 2018/2019 y 2020/2021, respectivamente.\
Las infecciones respiratorias agudas (IRAs) se clasifican en:
1) Las ETI o enfermedades tipo influenza son aquellos procesos agudos que incluyen fiebre y tos/dolor garganta sin causa aparente.\
2) Neumonía: se repiten los síntomas sumando un proceso de infiltración lobar o segmentario y/o derrame pleural. Un cuadro de mayor complejidad y riesgo.\
3) Bronquiolitis en menores de 2 años: definida como cualquier episodio de sibilancias que se acompañe de una infección viral, con o sin fiebre.\

### Interés

Personal: Relación directa con la profesión de grado -Ingeniería Biomédica-.
Impacto sanitario: Las infecciones respiratorias agudas (IRAs) están asociadas a procesos de comorbilidad y evolución en enfermedades complejas.\
Además, en el marco de la pandemia por COVID-19 su estudio y vigilancia se vuelven fundamentales para seguir comprendiendo el fenómeno pandémico.\

### Algunos interrogantes interesantes

¿Existe una distribución uniforme de los casos de IRAs en nuestro territorio?\
¿Están los casos positivos de IRAs asociadas a una época (estacionalidad)?\
¿Atento a la pandemia por COVID-19, los casos de IRAs según las series de tiempo se vieron modificados?\
¿Afectan las IRA principalmente a un grupo etario?
