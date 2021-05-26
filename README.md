# Reporte
 
# Vulnerabilidad 
Openluck

Kioptrix nivel 1 
# Descripcion 
SSL es una tecnología estandarizada que permite cifrar el tráfico de datos entre un navegador web y un sitio web (o entre dos servidores web), protegiendo así la conexión. Esto impide que un hacker pueda ver o interceptar la información que se transmite de un punto a otro, y que puede incluir datos personales o financieros.
Si aparecen las letras HTTPS al principio de la dirección (URL) de un sitio web, dicho sitio está protegido por un certificado SSL o TLS. Además, en la barra de direcciones del navegador aparece un icono de un candado y, al hacer clic sobre ese icono, los usuarios pueden consultar los datos del certificado, como la autoridad emisora y el nombre de la empresa propietaria del sitio web.

# Elementos con los que se trabajo 
Máquina virtual virtualvox kioptrix lvl 1

# Reproduccion
1-	En nuestra terminal primeramente es necesario encontrar la ip para poder conectarnos con kioptrix, y, la manera de acceder es mediante el comando supo arp-scan -l.

2-	Posteriormente, en este paso es donde se procede a escalar; utilizando el primer dato que es la ip y así poder obtener el puerto que se encuentre abierto.

3-  Luego de esto, podemos dar inicio a nuestro ataque.

4- Una vez iniciado el ataque, se comprometen los datos obtenidos anteriormente

# Impacto
Se da cuando el atacante ya tiene un total acceso a la información del sitio web, mismos que han podido ser captados mediante la vulnerabilidad y privilegios que se obtuvieron al acceder al sitio web, lo cual quiere decir, que todos los datos e información personal pasa a ser conocida para el atacante, tales como: Usuarios, bases de datos, contraseñas, entre otros.

# mitigacion 
1- Obtener certificado SSL

2- Configurar la red vpn 

3- Configurar un archivo .htaccess para evitar inyectar enrutamientos.

# Referencias 
https://md5.gromweb.com/?string=%241%24zL4.MR4t%2426N4YpTGceBO0gTX6TAky1

https://nvd.nist.gov/vuln/detail/CVE-2003-0201

https://github.com/heltonWernik/OpenLuck

https://www.digicert.com/es/what-is-ssl-tls-https/

# POC

![imagen 1](./fotos/img1.png)

![imagen 2](./fotos/img2.png)
