# Bufanda Rosa

Este programa permite **cifrar** y **descifrar** mensaje o archivos para: enviarlos por correo electrónico, publicarlo o compartir de modo anónimo (con TOR). 
También nos permitirá guardar información, de cualquier tipo, dentro de una **imagen**,  **archivo de audio** o generar códigos **QR** con el mensaje cifrado.

![captura del programa](img/cifrado.png)

## Instalar

<pre>
cd /tmp
wget https://raw.github.com/b4zz4/BufandaRosa/master/bufandarosa
bash bufandarosa -u
</pre>

## Proxy de IRC cifrado

Genera un proxy local de IRC que cifra los mensajes de entrada y salida en base a una clave.
Esta basado en el concepto de [dirtirc](http://dirtirc.sf.net) pero con un cifrado mucho más complejo basado en `GPG`.

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

## Quehaceres

* Imágenes al azar de diversas fuentes
* Publicación de imágenes automática
* Cifrar usando [OTR](http://www.cypherpunks.ca/otr/)
* hacer que el cifrado del IRC sea multiparty (basado en OTR)

# Wgetpaste

Intento mantener la ultima versión. [Sitio original](http://wgetpaste.zlin.dk/)
