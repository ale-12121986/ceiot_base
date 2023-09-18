### Sistema de adquisición de datos para maquinaria pesada de vía 

Objetivo del ataque: alterar los valores de medición de la vía para generar deformación sobre la misma.
##Descripcion
Este sistema se va a encargar de adquirir los valores de nivel, peralte, alineación y distancia recorrida al momento que la maquinaria pesada de vía se encuentre realizando trabajos de mejoramiento de vía, estos datos son enviados en tiempo real a una base de datos en la nube para poder ser vistos y analizados por el personal encargado. estos datos adquiridos no solo van a ser manipulados por pocas personas.
Se van a utilizar los servicios en la nube para tener los servidores y va a tener una interfaz grafica amigable donde se pueden ver los datos obtenidos del trabajo de mejoramientos realizados
* Reconnaissance
  - Busco los Correos o números de teléfonos de los coordinadores. 
Gather Victim Identity Information: T1589
Phishinh for Information: T1598 
  - Busco las bateadoras que tienen el sistema instalado y buscando en los manuales ver como se conecta a la red.
Gather Victim Network Information: T1590
* Weaponization
  - Voy buscar un malware en la red (SPYWARE) que infecte el equipo del usuario y así obtener los datos para entrar en el sistema. 
 Obtian Capabilities: T1588
Develop Capailitiers: T1587
* Delivery
  - Voy realizar ataques de ingeniería social o phishing para engañar a los usuarios finales o personal de mantenimiento para que descarguen el malware en el sistema, enviando email y mensaje de whatsapp haciéndome pasar por la gerencia de la empresa.
Spearphishing Attachment: T1566.001
Trusted RelationShip: T1199 
* Exploit
  - El malware (SPYWARE) puede explotar vulnerabilidades conocidas o en el software del sistema para generar acceso no autorizado.
  
* Installation  
  - Una vez asegurado el acceso al computador de los coordinadores o el personal de mantenimiento puedo instalar el malware en el equipo de alguno de ellos, y cuando realicen una conexión física con el sistema en la bateadora, puedo instalar leer o modificar el firmware para lograr una manipulación de los datos.

* Command & Control
  - Establezco una comunicación encubierta con los dispositivos comprometidos, lo que me permite tomar el control y recopilar el valor de los sensores y ver los datos guardados en la base de datos.
  
* Actions on Objectives
  - Puedo manipular datos para enviar información incorrecta o destructiva a la nube, lo que puede resultar errores en la base datos o acciones incorrectas por parte de los coordinadores.
Data Encoding: T1132
Web Service: T1102
