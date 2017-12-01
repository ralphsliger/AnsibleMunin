
##Ansible con Munin, Apache y Jmeter

Munin es un programa de monitorización de servidores que genera estadísticas sobre su funcionamiento de los recursos de nuestros servidores, como memoria, disco duro y servicios. Utiliza las herramientas RRDTool para generar gráficas de rendimiento de los parámetros del sistema analizados. Utiliza una interfaz web para mostrar las gráficas generadas, permite trabajar de forma distribuida, mostrando la información de varios servidores. Para ello se instala en una SERVER la parte servidora de Munin y en el resto la parte cliente, que mandará los datos recopilados al servidor para que éste los muestre. 

##Implementación
Primero se accede a la carpeta del proyecto  por medio de la terminal y sigue las instrucciones.
Luego, se debe realizar la ejecución de los playbooks para ello ingresar a la carpeta ansible y ejecutar las instrucciones de ese directorio.
