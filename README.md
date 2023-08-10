# Generalidades
Generalidades del complemento QoilTools  

   Sobre el Complemento  
   =====================  
   QoilTools es el complemento principal del entorno que facilita el uso de QGIS en la caracterización de yacimientos. Potencial el uso y tratamiento de la información de subsuelo generada o de fuentes externas, su categorización, asignación de estilos, cartografiado, presentación y certificación, resguardo eficiente en Bases de Datos, Geopackage, Geojson, Shape File, entre otros. Todo esto,  a través de una interfaz sencilla e intuitiva, maximizando la eficiencia de los algoritmos nativos de QGIS y propios, junto a elemento como las librerías de simbologías necesarias en la industria de O&G. EL entorno que conforma QoilTools y QGIS facilitan el acceso a la información a un mayor grupo de usuarios, permite el seguimiento, actualización y oficialización de los datos con el máximo de seguridad y confidencialidad, adicionalmente consolida el uso de información digital válida y certificada, reduciendo el uso de impresiones en papel.  
   
   Lenguaje  
   ========  
   Los códigos de QoilTools está escrito en lenguaje **Python**, las ventanas fueron creadas en **Qt5**.  

   Desarrollador  
   =============  
   Tanto QoilTools, QMapSymbolVE, QMapSymbol, las librerías y todo lo relacionado al entorno que permite potenciar a QGIS como la herramienta para trabajar con datos de subsuelo y superficie en la caracterización y explotación de yacimientos en la industria de O&G fue realizado por el Geólogo Aldo Sardelli asardelli@gmail.com  

   Instalación  
   ===========  
   El complemento solo está disponible para ser instalado a través de un archivo ZIP en “Administrar e instalar complementos”.  

   <p align="center">
<img src="img/Ge_1.png"  width="800" alt="Ventana de instalación de complementos de QGIS">
</p>  

- Se selecciona Instalar a partir de ZIP.
- Se busca la carpeta comprimida QoilTools.zip.

<p align="center">
<img src="img/Ge_2.png"  width="800" alt="Ventana explorador para ubicar el archivo">  
</p>

- Seleccionado el archivo instalador se activa el botón “Instalar complemento”

<p align="center">
<img src="img/Ge_3.png"  width="800" alt="Ventana de instalación de complementos de QGIS con el archivo seleccionado">  
</p>  

- Se hace clic y aparece un mensaje *La instalación de un complemento de una fuente no confiable puede dañar su computadora. Continúe solo si recibió el complemento de una fuente confiable. ¿Continuar?.*

<p align="center">
<img src="img/Ge_4.png"  width="400" alt="Mensaje de confiabilidad del archivo">  
</p>  

- Clic sobre el botón *Si*.

  **¡Listo! El complemento fue instalado.**

  Variables
  =========
  Para mejorar la experiencia con la interfaz se debe definir una variable Global ***user_country*** al momento de la instalación.  

<p align="center">
<img src="img/Ge_5.png"  width="600" alt="Ventana propiedades del proyecto QGIS">  
</p>  

Procedimiento para agregarla:
- En el menú Configuración, Opciones se hace clic y aparece la ventana de opciones.

<p align="center">
<img src="img/Ge_6.png"  width="600" alt="Ventana de Opciones-Variables de QGIS">  
</p>  

- Se hace clic en el símbolo más (+) en color verde ubicado en la parte inferior derecha.

<p align="center">
<img src="img/Ge_7.png"  width="600" alt="Ventana de Opciones-Variables de QGIS al agregar la nueva variable">  
</p>  

- Al hacer clic, se agrega una nueva variable a la que se le asigna el nombre ***user_country*** y como valor ***Venezuela***.

**¡Listo! La variable a sido agregada.**  

<p align="center">
<img src="img/Ge_8.png"  width="600" alt="Ventana de Opciones-Variables de QGIS con la variable user_country agregada">  
</p>  

   Procesos  
   ========  
   El complemento cuenta con 55 procesos distribuidos en 16 botones:  

•	Crear capa nueva (QoilCn)  
•	Transformar puntos a líneas (QoilCo)  
•	Transformar líneas a polígono (QoilCo)  
•	Transformar polígonos a líneas (QoilCo)  
•	Transformar líneas a puntos (QoilCo)  
•	Cargar pozos por lotes (QoilCp)  
•	Cargar un pozo (QoilCp)  
•	Definir parámetros geológicos (QoilDg)  
•	Crear Yacimiento (QoilYo)  
•	Buscar pozos por yacimientos (QoilYo)  
•	Definir acumulación (QoilDa)  
•	Cálculo de Datos Estructurales (QoilDe)  
•	Calculo de azimut (QoilDe)  
•	Plano de referencia de yacimientos (QoilDe)  
•	Espacio cero (QoilDe)  
•	Transferir Valores Máx/Mín (QoilTf)  
•	Transferir Datos (QoilTf)  
•	Inspector de Rangos (QoilTf)  
•	Ajuste de Valle y Cima (QoilTf)  
•	Calcular área (QoilAr)  
•	Cálculo de Espesor Promedio (QoilVo)  
•	Cálculo de volumen (QoilVo)  
•	Transferir valor (QoilVo)  
•	Tabla Resumen (QoilVo)  
•	Unir Capas (QoilUn)  
•	Agregar objetos a capa (QoilUn)  
•	Dividir capa (QoilDi)  
•	Copiar Atributo de una capa a otra (QoilCa)  
•	Cálculo Dinámico (QoilUt)  
•	Campo Nuevo (QoilUt)  
•	Transformar Partes (QoilUt)  
•	Cambiar el Nombre a la Capa (QoilUt)  
•	Constante (QoilUt)  
•	Constante Numérica (QoilUt)  
•	Incremental (QoilUt)  
•	Constante con Incremental (QoilUt)  
•	Fecha Actual (yyyy/MM/dd) (QoilUt)  
•	Hora (HH/mm/ss) (QoilUt)  
•	Fecha y Hora Actual (QoilUt)  
•	Fecha Específica (yyyy/MM/dd) (QoilUt)  
•	Operación entre un Campo A y un Campo B (QoilUt)  
•	Operación entre un Campo A y una constante numérica (QoilUt)  
•	Borra atributos de un campo (QoilUt)  
•	Agregar un Punto por Coordenadas (QoilUt)  
•	Agregar Puntos, una Línea o un Polígono por coordenadas (QoilUt)  
•	Corregir geometrías (QoilUt)  
•	Agregar Alias a los campos de atributos (QoilUt)  
•	Quitar Alias (QoilUt)  
•	Asignar Alias (Sobrenombre) individual (QoilUt)  
•	Quitar Alias (Sobrenombre) individual (QoilUt)  
•	Mostrar la ubicación de la capa (QoilUt)  
•	Evaluar las geometrías (QoilUt)  
•	Evaluar campos (QoilUt)  
•	Mostrar Tabla de Atributos (QoilTa)  
•	Eliminar capa(s) seleccionadas (QoilEl)  

   Botones
   =======  
   QoilTools cuenta con 16 botones de los cuales 14 abren una ventana y 2 ejecutan un proceso directo.  


| Nombre | Símbolo Botón | Ventana/Directo | Pestañas | N° Procesos |
| :---: | :---: | :---: | :---: | :---: |
| QoilUn | <img src="img/Ge_9.png"  width="50" alt="QoilUn">  | Ventana | 1 | 1 |
| QoilCo | <img src="img/Ge_10.png"  width="50" alt="QoilCo"> | Ventana | 2 | 4 |
| QoilCp | <img src="img/Ge_11.png"  width="50" alt="QoilCp"> | Ventana | 2 | 2 |
| QoilDg | <img src="img/Ge_12.png"  width="50" alt="QoilDg"> | Ventana | 1 | 1 |
| QoilYo | <img src="img/Ge_13.png"  width="50" alt="QoilYo"> | Ventana | 2 | 2 |
| QoilDa | <img src="img/Ge_14.png"  width="50" alt="QoilDa"> | Ventana | 1 | 1 |
| QoilDe | <img src="img/Ge_15.png"  width="50" alt="QoilDe"> | Ventana | 3 | 3 |
| QoilTf | <img src="img/Ge_16.png"  width="50" alt="QoilTf"> | Ventana | 3 | 4 |
| QoilAr | <img src="img/Ge_17.png"  width="50" alt="QoilAr"> | Ventana | 1 | 1 |
| QoilVo | <img src="img/Ge_18.png"  width="50" alt="QoilVo"> | Ventana | 4 | 4 |
| QoilUn | <img src="img/Ge_19.png"  width="50" alt="QoilUn"> | Ventana | 2 | 2 |
| QoilDi | <img src="img/Ge_20.png"  width="50" alt="QoilDi"> | Ventana | 1 | 1 |
| QoilCa | <img src="img/Ge_21.png"  width="50" alt="QoilCa"> | Ventana | 1 | 1 |
| QoilUt | <img src="img/Ge_22.png"  width="50" alt="QoilUt"> | Ventana | 5 | 25 |
| QoilTa | <img src="img/Ge_23.png"  width="50" alt="QoilTa"> | Directo | 1 | 1 |
| QoilEl | <img src="img/Ge_24.png"  width="50" alt="QoilCa"> | Directo | 1 | 1 |

   Accesibilidad  
   =============  
   El acceso desde el sistema se puede hacer a través de la barra de menu, una Barra de herramienta, Barra de menú en la parte superior de panel de capas y un sub-menu en el menú de la capa (botón derecho del mouse).
   - ## Menú
     Todas las ventanas de QoilTools pueden accederse a través de menú ***QoilTools*** en la barra de menu de QGIS. adicioanlmente es donde se encuentran los manuales de uso del complemento.

     
<p align="center">
<img src="img/Ge_25.png"  width="600" alt="Menú QoilTools enla barra de menú de QGIS">  
</p>  
