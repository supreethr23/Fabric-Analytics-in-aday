# **Microsoft Fabric - Fabric Analyst in a Day - Lab 7**

![](../media/lab-07/main7.png)

# Contenido

- Introducción	
- Power BI
	- Tarea 1: Crear un informe de forma automática
	- Tarea 2: Configurar el fondo para un nuevo informe
	- Tarea 3: Agregar un encabezado al informe
	- Tarea 4: Agregar KPI al informe
	- Tarea 5: Agregar un gráfico de líneas al informe
	- Tarea 6: Guardar el informe
	- Tarea 7: Configurar la columna Year en la tabla Date	
	- Tarea 8: Configurar la columna Month Name en la tabla Date	
	- Tarea 9: Aplicar formato al gráfico de líneas	
	- Tarea 10: Conectar Power BI Desktop al modelo semántico	
	- Tarea 11: Agregar nuevos datos para simular el modo Direct Lake	
- Limpieza del entorno de laboratorio	
- Referencias	

# Introducción 
En este curso, se le ha presentado el almacén de lago de datos, se ingieren datos de diferentes orígenes de datos en el almacén de lago de datos, se establece un calendario de actualización para las orígenes de datos y se crea un modelo de datos. Ahora vamos a crear un informe.

Al final de este laboratorio, habrá aprendido: 
- Cómo crear un informe de forma automática
- Cómo crear un informe a partir de un lienzo en blanco
- Cómo crear un informe con Power BI Desktop
- Cómo usar el modo Direct Lake, que da como resultado una actualización automática de los datos

# Power BI

## Tarea 1: Crear un informe de forma automática
Comencemos con la opción de creación automática de informes. Y, más adelante en el laboratorio, volveremos a crear el informe que tenemos en Power BI.

1. 	Volvamos al área de trabajo de Fabric que creó en el laboratorio anterior.

2. 	En la parte inferior del panel de navegación de la izquierda, seleccione el icono Selector de experiencia de Fabric.

3. 	Se abre el cuadro de diálogo de experiencia de Fabric. Seleccione Power BI. Se le llevará a la página Inicio de Power BI.

![](../media/lab-07/main7.png)

4. 	Seleccione Nuevo informe en el menú superior.

![](../media/lab-07/main7.png)

5. 	Se le dirigirá a la pantalla Crear el primer informe. Habrá opciones para crear un informe usando Excel, CSV, introducir datos manualmente y crear un informe o elegir un modelo semántico publicado. Hemos creado un modelo semántico en los laboratorios anteriores. Usemos ese. Seleccione la opción Selección de un modelo semántico publicado.

![](../media/lab-07/main7.png)

6. 	Se abre la página Elija un conjunto de datos para usar en su informe. Observe que tenemos varias opciones. Seleccione sm_FAIAD.

	a.	**sm_FAIAD**: este es el modelo semántico que hemos creado y que queremos utilizar para crear el informe.
	b.	**lh_FAIAD**: este es el almacén de lago de datos en el que ingerimos todos los datos.
	c.	**Units by Supplier**: este es el conjunto de datos que creamos con T-SQL.
	d.	**DataflowsStagingWarehouse**: este es el almacén provisional que se crea de manera predeterminada. No utilizamos esto porque no organizamos datos.
	e.	**DataflowsStagingLakehouse**: este es el Lakehouse provisional que se crea de manera predeterminada. No utilizamos esto porque no organizamos datos.

7. 	Haga clic en la flecha **junto al botón Crear informe de forma automática**. Observe que hay dos opciones: Crear informe de forma automática y Crear un informe en blanco. Probemos la creación automática: seleccione **Crear informe de forma automática**.





