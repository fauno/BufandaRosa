# ![captura del programa](img/bufandarosa.png) Bufanda Rosa


Este programa permite **cifrar** y **descifrar** mensaje o archivos para: enviarlos por correo electrónico, publicarlo o compartir de modo anónimo (con TOR). 
También nos permitirá guardar información, de cualquier tipo, dentro de una **imagen**,  **archivo de audio** o generar códigos **QR** con el mensaje cifrado.
Y chatear de modo cifrado en cualquier servidor de IRC.

![captura del programa](img/cifrado.png)

## Instalar

<pre>
cd /tmp
wget https://raw.github.com/b4zz4/BufandaRosa/master/bufandarosa
bash bufandarosa -u
</pre>

## Proxy de IRC cifrado

![captura del programa](img/irc.png)

Genera un proxy de cualquier servidor de IRC (sin SSL) cifrando y descifrando los mensajes de entrada y salida (con clave).
Esta inspirado en el concepto de [dirtirc](http://dirtirc.sf.net), pero con un cifrado mucho más fuerte basado en `GPG`.
Lo único que necesitas es coordinar previamente que clave van a utilizar.

## Vieja escuela

Linea de comandos para Bufanda Rosa.

<pre>
echo "echo 'hola mundo' | pastie" | bufandarosa -c
</pre>
> publica `hola mundo` en un pastie de modo anonimo

<pre>
echo ayuda | bufandarosa -c
</pre>
> ayuda de la versión de terminal

<pre>
echo "irc 'irc.freenode.net 6667' clave 6667" | bufandarosa -c
</pre>
> Genera un proxy de freenode cifrado (NO anonimiza la conexión)

## Quehaceres

* Imágenes al azar de diversas fuentes
* Publicación de imágenes automática
* Cifrar usando [OTR](http://www.cypherpunks.ca/otr/)
* hacer que el cifrado del IRC sea multiparty (basado en OTR)
  * Soporte para SSL
  * Tor para freenode
* Leer feed en busqueda de mensajes cifrados

# Wgetpaste

Intento mantener la ultima versión. [Sitio original](http://wgetpaste.zlin.dk/)
