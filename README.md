
# Visualizacion de Pawer BI con Hive

## Introducción
Esta es la guie para poder conectar Hadoop + YARN + Hive + PowerBI a la misma vez.

## 0. Preparativos
Para ello lo primero que debemos de tener en pie los contenedores de Hive, como ya se indicó en esta practica:

```bash
https://github.com/SergioFerrerasRuiz/HadoopYarnHive
```
Una vez se hallan completados los pasos, podremos seguir con esta practica.



## 1. Instalacion de PowerBI
Ahora deberemos instalar Power Bi Desktop desde la microsoft store y seguir los siguientes pasos para su configuración
![Foto de proyecto](assets/1.png)
![Foto de proyecto](assets/2.png)
![Foto de proyecto](assets/3.png)
### Dentro de PowerBI

### 1.  Click
Haz click en "obtener datos de otros orígenes"
![Foto de proyecto](assets/4.png)
### 2. Seleccion Hive
En el menu izquierdo haz click en otros y selecciona Hive
![Foto de proyecto](assets/5.png)
### 3. Configuracion servidor
Ahora se te pedira el servidor donde que estableceremos el que hayas escogido en el contenedor de hive, en mi caso utilizé "localhost:9083" y poner el nombre de la base da datos que quieras cargar en este caso "libreria"
Respecto al thrif deberemos seleccionar estandar y la conectividad de datos "importar"
![Foto de proyecto](assets/6.png)
### 4. Acceso Credenciales
En nombre de ususario y contraseña deberemos poner "root"
![Foto de proyecto](assets/7.png)
### 5. Visualizacion
Ya podremos ver la tabla en Power BI con nuestros datos cargados desde la base de datos de hive
![Foto de proyecto](assets/8.png)
![Foto de proyecto](assets/9.png)
![Foto de proyecto](assets/10.png)
### 6. Valoracion de Datos
En la derecha en datos desplegamos la tabla donde observamos un gráfico con los datos de nuestra nuestra tabla.
![Foto de proyecto](assets/11.png)

   