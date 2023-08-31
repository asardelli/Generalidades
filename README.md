# Generalidades
Generalidades del complemento QoilTools  

   Sobre el Complemento  
   =====================  
   <p style="text-align: justify;">QoilTools es el complemento principal del entorno que facilita el uso de QGIS en la caracterización de yacimientos. Potencial el uso y tratamiento de la información de subsuelo generada o de fuentes externas, su categorización, asignación de estilos, cartografiado, presentación y certificación, resguardo eficiente en Bases de Datos, Geopackage, Geojson, Shape File, entre otros. Todo esto,  a través de una interfaz sencilla e intuitiva, maximizando la eficiencia de los algoritmos nativos de QGIS y propios, junto a elemento como las librerías de simbologías necesarias en la industria de O&G. EL entorno que conforma QoilTools y QGIS facilitan el acceso a la información a un mayor grupo de usuarios, permite el seguimiento, actualización y oficialización de los datos con el máximo de seguridad y confidencialidad, adicionalmente consolida el uso de información digital válida y certificada, reduciendo el uso de impresiones en papel.</p>  
   
   Lenguaje  
   ========  
   Los códigos de QoilTools está escrito en lenguaje **Python**, las ventanas fueron creadas en **Qt5**.  

   Desarrollador  
   =============  
   <p style="text-align: justify;">Tanto QoilTools, QMapSymbolVE, QMapSymbol, las librerías y todo lo relacionado al entorno que permite potenciar a QGIS como la herramienta para trabajar con datos de subsuelo y superficie en la caracterización y explotación de yacimientos en la industria de O&G fue realizado por el Geólogo Aldo Sardelli asardelli@gmail.com</p>  

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
<img src="img/Ge_25.png"  width="500" alt="Menú QoilTools enla barra de menú de QGIS">  
</p>  

   - ## Barra de Herramientas
     Se denomina ***QoilTools*** y abre todas las ventanas y ejecuta los dos procesos directos de abrir la Tabla de Atributros y eliminar la(s) capas seleccionadas.

<p align="center">
<img src="img/Ge_26.png"  width="600" alt="Barra de Herramienta QoilTools">  
</p>  
   
   Los botones en la barra de herramienta están agrupados en cinco grupos:
   - El primero contiene los procesos de creación de información vectorial primaria (QoilCn, QoilCo y QoilCp).
   - El segundo grupo está orientado a caracterización geológica, creación de yacimientos y su definición, así como análisis estructural (QoilDg, QoilYo, QoilDa y QoilDe).
   - El tercer grupo asociado a cálculo de área y volumen con algunas herramientas para transferir información (QoilTf, QoilAr y QoilVo).
   - Un cuarto grupo contentivo de procesos para agregar y transformar información (QoilUn, QoilDi, QoilCa y QoilUt).
   - Finalmente, el quinto grupo donde se encuentran los botones de procesos directos, para abrir la Tabla de Atributos y eliminar la(s) capas seleccionadas (QoilTa y QoilEl).
   
  - ## Barra de herramienta del panel de capas
    En esta barra ubicada en la parte superior del panel de capas se pueden encontrar los botones que ejecutan procesos directos como Abrir Tabla de Atributo (QoilTa) y Elimina la(s) capas seleccionadas (QoilEl).

<p align="center">
<img src="img/Ge_27.png"  width="300" alt="Barra de Herramienta del panel de capas">  
</p>  

   - ## Sub-menú en el menú de la capa
     <p style="text-align: justify;">Este menu se encuentra al al hacer clic con el botón derecho del mouse y se encuentran los tres procesos de uso frecuente para las capas vectoriales: Crear capa vector a partir de otra (QoilCo), Definir parámetros geológicos (QoilDg) y Herramientas adicionales (QoilUt), dentro de un menu llamado ***QoilTools***.</p>

<p align="center">
<img src="img/Ge_28.png"  width="600" alt="Barra de Herramienta de la capa">  
</p>  

   Tips
   ====
   Cada ventana cuenta con tips que indican el uso o concepto necesario para entender la variable. Son mostrados al posar el puntero sobre cualquier elemento de la ventana.  

A continuación, los enlaces si desea conocer los tips para cada ventana, recuerde que la posición de la etiqueta de los tips no siempre son las mostrada en las imágenes.

[Ventana QoilCn](img/Ge_29.png)  
[Ventana QoilCo Pestaña 1](img/Ge_30.png)  
[Ventana QoilCo Pestaña 2](img/Ge_31.png)  
[Ventana QoilCp Pestaña 1](img/Ge_32.png)  
[Ventana QoilCp Pestaña 2](img/Ge_33.png)  
[Ventana QoilDg](img/Ge_34.png)  
[Ventana QoilYo Pestaña 1](img/Ge_35.png)  
[Ventana QoilYo Pestaña 2](img/Ge_36.png)  
[Ventana QoilDa](img/Ge_37.png)  
[Ventana QoilDe Pestaña 1](img/Ge_38.png)  
[Ventana QoilDe Pestaña 2](img/Ge_39.png)  
[Ventana QoilDe Pestaña 3](img/Ge_40.png)  
[Ventana QoilTf Pestaña 1](img/Ge_41.png)  
[Ventana QoilTf Pestaña 2](img/Ge_42.png)  
[Ventana QoilTf Pestaña 3](img/Ge_43.png)  
[Ventana QoilAr](img/Ge_44.png)  
[Ventana QoilVo Pestaña 1](img/Ge_45.png)  
[Ventana QoilVo Pestaña 2](img/Ge_46.png)  
[Ventana QoilVo Pestaña 3](img/Ge_47.png)  
[Ventana QoilVo Pestaña 4](img/Ge_48.png)  
[Ventana QoilUn Pestaña 1](img/Ge_49.png)  
[Ventana QoilUn Pestaña 2](img/Ge_50.png)  
[Ventana QoilDi](img/Ge_51.png)  
[Ventana QoilCa](img/Ge_52.png)  
[Ventana QoilUt Pestaña 1](img/Ge_53.png)  
[Ventana QoilUt Pestaña 2](img/Ge_54.png)  
[Ventana QoilUt Pestaña 3](img/Ge_55.png)  
[Ventana QoilUt Pestaña 4](img/Ge_56.png)  
[Ventana QoilUt Pestaña 5](img/Ge_57.png)  

   Proceso Intuitivos  
   ==================
   Las ventanas del complemento QoilTools cuentan con un sistema intuitivo para ayudar al usuario a definir los parámetros requeridos de manera correcta. Los cuales se describen a continuación:  

   - ## Activación de Check
   <p style="text-align: justify;">Los Check se activarán cuando sea seleccionado el parámetro que lo define, tales como: escribir el nombre de un campo, seleccionar el tipo de campo, seleccionar una capa, seleccionar el tipo de archivo, o abrir el explorador para guardar un archivo.</p>  
   De la misma manera se deseleccionará cuando la asignación o selección de algún parámetro vuelve a su estado inicial.
   - ## Sugerencias
   En los parámetros de nombre de capa o nombre de archivo el sistema sugerirá uno según el nombre o tipo de la capa de entrada.

   - ## Sistema de semáforo  
   Dependiendo de la selección de los parámetros, el sistema indicará a taves de colores en el botón de ejecución o la etiqueta asociada al parámetro.
     Estos elementos cambiarán entre los colores ***Amarillo***, ***Rojo*** y ***Verde***.
     El color amarillo indica que los parámetros no han sido completados.  
	
<p align="center">
<img src="img/Ge_58.png"  width="100" alt="Ejemplo de un botón de ejecuación color amarillo">  
</p>

   El color Rojo indica que un parametros es incorrecto, no válido o incompleto por lo que el proceso no podra ejecutarse.  
     
<p align="center">
<img src="img/Ge_59.png"  width="100" alt="Ejemplo de un botón de ejecuación color rojo">  
</p>

   Cuando las etiquetas y/o el botón de ejecutar cambia su color a verde, indica que el parámetro es correcto, que todos los requerimeintos fueron cumplidos y el proceso se ejecutara correctamente.  
<p align="center">
<img src="img/Ge_60.png"  width="100" alt="Ejemplo de un botón de ejecuación color verde">  
</p>  

   Mensajes de Alertas y errores  
   =============================  
   QoilTools cuenta con un conjunto de mensajes clasificado de acuerdo a su origen en: Critico, Precaución, Informativo y Confirmación. A continuación, se presentan cada uno de ellos indicando la(s) ventana donde se podrían mostrar:  
	
   - ### Mensajes Acción Critica  
	
<p align="center">
<img src="img/Ge_61.png"  width="400" alt="Ventana emergente El nombre de la capa no debe contener caracteres especiales">  
</p> 

Ventanas QoilCn, QoilCo, QoilCp, QoilYo.  

<p align="center">
<img src="img/Ge_62.png"  width="400" alt="Ventana emergente El nombre de los campos no debe contener caracteres especiales">  
</p> 

Ventanas QoilCn, QoilCa, QoilUt.  

<p align="center">
<img src="img/Ge_63.png"  width="300" alt="Ventana emergente No admite caracteres especiales">  
</p> 

Ventanas QoilCn, QoilCo,QoilDg, QoilYo, QoilTf, QoilUn, QoilDi, QoilCa, QoilUt.  

<p align="center">
<img src="img/Ge_64.png"  width="420" alt="Ventana emergente No se puede leer el archivo Datos Generales">  
</p> 

Ventana QoilCp. 

<p align="center">
<img src="img/Ge_65.png"  width="420" alt="Ventana emergente No se puede leer el archivo Survey">  
</p> 

Ventana QoilCp. 

<p align="center">
<img src="img/Ge_66.png"  width="420" alt="Ventana emergente El Proceso no puede ejecutarse">  
</p> 

Ventana QoilCp. 

<p align="center">
<img src="img/Ge_67.png"  width=300" alt="Ventana emergente Alguna de las capa no es válida">  
</p> 

Ventana QoilYo. 

<p align="center">
<img src="img/Ge_68.png"  width=250" alt="Ventana emergente Capa de Entrada no válida">  
</p> 

Ventanas QoilYo, QoilDe, QoilAr, QoilVo, QoilUn, QoilDi, QoilCa. 

<p align="center">
<img src="img/Ge_69.png"  width=450" alt="Ventana emergente El nombre de la Horizonte/Arena no debe contener caracteres especiales">  
</p> 

Ventana QoilDa. 

<p align="center">
<img src="img/Ge_70.png"  width=450" alt="Ventana emergente El prefijo del pozo no debe contener caracteres especiales">  
</p> 

Ventana QoilDa. 

<p align="center">
<img src="img/Ge_71.png"  width=450" alt="Ventana emergente El correlativo del pozo no debe contener caracteres especiales">  
</p> 

Ventana QoilDa. 

<p align="center">
<img src="img/Ge_72.png"  width=200" alt="Ventana emergente Capa no válida">  
</p> 

Ventanas QoilDa, QoilDa, QoilTf, QoilUt. 

<p align="center">
<img src="img/Ge_73.png"  width=400" alt="Ventana emergente La capa no posee valores de área ni de volumen">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_74.png"  width=300" alt="Ventana emergente La capa no posee valores de volumen">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_75.png"  width=300" alt="Ventana emergente La capa no posee valores de área">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_76.png"  width=450" alt="Ventana emergente No existen los campos OILFIELD_NAME, AREA y VOLUME">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_77.png"  width=300" alt="Ventana emergente Existen una capa a unir No válida">  
</p> 

Ventana QoilUn.  

<p align="center">
<img src="img/Ge_78.png"  width=300" alt="Ventana emergente Existen una capa a copiar No válida">  
</p> 

Ventana QoilCa.  

<p align="center">
<img src="img/Ge_79.png"  width=300" alt="Ventana emergente Constante numérica No válida">  
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_80.png"  width=400" alt="Ventana emergente La Capa no permite transformación">  
</p> 

Ventana QoilUt. 

<p align="center">
<img src="img/Ge_117.png"  width=450" alt="Ventana emergente La Capa no es un polígono, Cierra la ventana principal, seleccioan la capa correcta e inicia el proceso nuevamente">  
</p> 

Ventana QoilUt. 

   - ### Mensajes de Precaución  

<p align="center">
<img src="img/Ge_81.png"  width="300" alt="Ventana emergente Seleccione el tipo de geometría">  
</p> 

Ventanas QoilCn, QoilUn.  

<p align="center">
<img src="img/Ge_82.png"  width="300" alt="Ventana emergente Completar los parámetros">  
</p> 

Ventanas QoilCn, QoilCo, QoilCp, QoilDg, QoilYo, QoilDa.  

<p align="center">
<img src="img/Ge_83.png"  width="350" alt="Ventana emergente Debe asignar un nombre a la nueva Capa">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_84.png"  width="450" alt="Ventana emergente Se ha desactivado el check a una capa Cierre, por favor active nuevamente o deseleccione la capa para continuar">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_85.png"  width="400" alt="Ventana emergente El nombre de la capa no debe tener caracteres especiales">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_86.png"  width="350" alt="Ventana emergente Seleccione las capas que definirán el yacimiento">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_87.png"  width="450" alt="Ventana emergente La capa contiene elementos no estructurales, el proceso no se podrá ejecutar">  
</p> 

Ventana QoilDe.  

<p align="center">
<img src="img/Ge_88.png"  width="400" alt="Ventana emergente No hya elementos seleccionados, desactive la opción Solo Seleccionados">  
</p> 

Ventana QoilDe.  

<p align="center">
<img src="img/Ge_89.png"  width="350" alt="Ventana emergente La profundidad de referencia no es numérica">  
</p> 

Ventana QoilDe.  

<p align="center">
<img src="img/Ge_90.png"  width="350" alt="Ventana emergente El campo de atributo INSPECCION no existe">  
</p> 

Ventana QoilTf.  

<p align="center">
<img src="img/Ge_90.png"  width="350" alt="Ventana emergente El campo de atributo INSPECCION no existe">  
</p> 

Ventana QoilTf.  

<p align="center">
<img src="img/Ge_91.png"  width="450" alt="Ventana emergente Se ha desactivado el check a una capa a unir, por favor active nuevamente o deseleccione la capa para continuar">  
</p> 

Ventana QoilUn.  

<p align="center">
<img src="img/Ge_92.png"  width="450" alt="Ventana emergente Se ha desactivado el check a una capa guía, por favor active nuevamente o deseleccione la capa para continuar">  
</p> 

Ventana QoilDi.  

<p align="center">
<img src="img/Ge_93.png"  width="250" alt="Ventana emergente Coordenadas No Válidas, Introduzca correctamente los valores">  
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_94.png"  width="300" alt="Ventana emergente La geometrías de la capa son válidas">  
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_95.png"  width="300" alt="Ventana emergente El campo no tiene un alia asociado">  
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_96.png"  width="400" alt="Ventana emergente No hay objetos seleccionados, desactiva Solo Seleccionados">  
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_97.png"  width="420" alt="Ventana emergente IMPORTANTE. Una vez ejecutado el proceso , la acción no se podra revertir. Este atento">  
</p> 

Ventana QoilUt.  

   - ## Mensajes de Información

<p align="center">
<img src="img/Ge_98.png"  width="250" alt="Ventana emergente El TVDSS es mayor al del pozo">  
</p> 

Ventana QoilCp.  

<p align="center">
<img src="img/Ge_99.png"  width="400" alt="Ventana emergente Los Sisitemas de Referecias de las capas Elementos son distintos. Se recomienda revisar los resultados">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_100.png"  width="300" alt="Ventana emergente La capa no contiene un campo Arena, no se pude conocer su nombre">  
</p> 

Ventana QoilDa.  

<p align="center">
<img src="img/Ge_101.png"  width="250" alt="Ventana emergente La capa An R3 es de tipo línea, Este proceso no admite como entrada este tipo de capa">  
</p> 

Ventanas QoilTf, QoilAr, QoilVo, QoilDi.  

<p align="center">
<img src="img/Ge_102.png"  width="200" alt="Ventana emergente No hay objetos a ajustar">  
</p> 

Ventana QoilTf.  

<p align="center">
<img src="img/Ge_103.png"  width="300" alt="Ventana emergente La capa activa no tiene le campo ID_YAC, Seleccioane una nueva capa">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_104.png"  width="350" alt="Ventana emergente La capa no tiene Yacimientos con Capa de Gas, Seleccioane una nueva capa">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_105.png"  width="320" alt="Ventana emergente La capa no identifica el tipo de yacimiento, Seleccioane una nueva capa">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_106.png"  width="450" alt="Ventana emergente Los datos de Area y Volumen deben corresponder a objeto parte en la capa y ser correctos, Para usarlos marque el los items Área y Volumen">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_107.png"  width="450" alt="Ventana emergente La capa no tiene los campos de atributos: NOMBRE y VOLUMEN">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_108.png"  width="350" alt="Ventana emergente La capa no tiene el campo de atributo: VOLUMEN">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_109.png"  width="350" alt="Ventana emergente La capa no tiene el campo de atributo: ÁREA">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_110.png"  width="450" alt="Ventana emergente Los sistemas de referencias de las capas a unir son distintos. Se recomienda revisar que todos los objetos espaciales esten ubicados correctamente en la capa a unida">  
</p> 

Ventana QoilUn.  

<p align="center">
<img src="img/Ge_111.png"  width="450" alt="Ventana emergente Los sistemas de referencias de las capas a unir son distintos al de la capa unida. Se recomienda revisar que todos los objetos espaciales esten ubicados correctamente en la capa a unida">  
</p> 

Ventana QoilUn.  

<p align="center">
<img src="img/Ge_112.png"  width="450" alt="Ventana emergente La capa no se dividio. Te sugiero...">  
</p> 

Ventana QoilDi.  

<p align="center">
<img src="img/Ge_113.png"  width="450" alt="Ventana emergente Los CRS de las capas a copiar son distintos al de la capa de entrada. Revisa que el atributo se haya copiado correctamente">  
</p> 

Ventana QoilCa.  

<p align="center">
<img src="img/Ge_114.png"  width="420" alt="Ventana emergente Los CRS de las capas a copiar son distintos entre ellos. Revisa que el atributo se haya copiado correctamente">  
</p> 

Ventana QoilCa.  

<p align="center">
<img src="img/Ge_115.png"  width="420" alt="Ventana emergente ATENCION La capa esta vacía, no tiene objetos espaciales">  
</p> 

Ventana QoilUt.  

   - ## Mensajes de Confirmación

<p align="center">
<img src="img/Ge_116.png"  width="250" alt="Ventana emergente ATENCION La capa CAMPOS COV , no tiene geometrías válidas">  
</p> 

Ventana QoilYo.  

<p align="center">
<img src="img/Ge_118.png"  width="450" alt="Ventana emergente ATENCION Se marco la opción para crear un campo nuevo, pero el campo existe, haz clic en">  
</p> 

Ventanas QoilAr,QoilVo.  

<p align="center">
<img src="img/Ge_119.png"  width="450" alt="Ventana emergente ATENCION Se marco la opción para crear un campo nuevo, pero el campo VOLUMEN existe, haz clic en">  
</p> 

Ventana QoilVo.  

<p align="center">
<img src="img/Ge_120.png"  width="320" alt="Ventana emergente ATENCION Los CRS de las capas guías son distintos. Haz clic en Aceptar para continuar o Cancelar para salir">  
</p> 

Ventana QoilDi.  

<p align="center">
<img src="img/Ge_121.png"  width="400" alt="Ventana emergente ATENCION Los CRS de las capas guías son distintos al del proyecto. Haz clic en Aceptar para continuar o Cancelar para salir">  
</p> 

Ventana QoilDi.  

<p align="center">
<img src="img/Ge_122.png"  width="450" alt="Ventana emergente ATENCION Para mantener la interoperabilidad de la información generada, se sugiere cambiar CAMPO por FIELD">  
</p>  

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_123.png"  width="300" alt="Ventana emergente ATENCION El campo FIELD se creo con éxito">
</p> 

Ventana QoilUt.  

<p align="center">
<img src="img/Ge_124.png"  width="300" alt="Ventana emergente ATENCION La operación se ejecutó con éxito">  
</p> 

Ventana QoilUt.  

   - ## Otros  
   ATENCIÓN. No se puede ejecutar.\nRevisa la selección de los parámetros.  
Ventana QoilVo  
   ATENCIÓN. Capa Buscar No Valida.  
Ventana QoilYo  
   ATENCIÓN. Revise los parámetros.  
Ventana QoilAr  
   ATENCIÓN. La capa Transferir no es válida.  
   ATENCIÓN. No se puede ejecutar.\nRevise los parámetros Max y Min o no existe un Campo de atributo ID.  
   ATENCIÓN. No hay objetos espaciales seleccionados.\nPresione el botón "Mostrar".  
Ventana QoilTf  
   ATENCIÓN. No se pudo generar el archivo.  
   ATENCIÓN. Capa de referencia No Válida.  
   ATENCIÓN. Capa intersección No Válida.  
Ventana QoilDe  
	
   Manuales
   ========
   Se prepararon 6 manuales de uso, segmentados para mejorar la experiencia con el usuario.
	
   [1.	Generalidades del complemento]()  
   [2.	Manual QoilCn QoilCo QoilCp](https://github.com/asardelli/Manual_QoilCn_QoilCo_QoilCp.git)  
   [3.	Manual QoilDg QoilYo QoilDa QoilDe](https://github.com/asardelli/Manual_QoilDg_OoilYo_QoilDa_QoilDe.git)  
   [4.	Manual QoilTf QoilAr QoilVo](https://github.com/asardelli/Manual_QoilTf_QoilAr_QoilVo.git)  
   [5.	Manual QoilUn QoilDi QoilCa](https://github.com/asardelli/Manual_QoilUn_QoilDi_QoilCa.git)  
   [6.	Manual QoilUt](https://github.com/asardelli/Manual_QoilUt.git)  

