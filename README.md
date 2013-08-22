# Bufanda Rosa

Este programa permite **cifrar** y **descifrar** mensaje o archivos para enviarlos por correo electrónico, publicarlo, compartir de modo anónimo. 
También nos permitirá guardar información de cualquier tipo dentro de una **imagen** o **audio** o generar códigos **QR** con el mensaje cifrado.

![captura del programa](img/cifrado.png)

## Instalar

<pre>
cd /tmp
wget https://github.com/b4zz4/BufandaRosa/archive/master.zip
unzip master.zip
cd BufandaRosa-master/
chmod +x bufandarosa
chmod +x wgetpaste
sudo cp wgetpaste /usr/bin/
./bufandarosa -i
</pre>


## Vieja escuela

Linea de comandos para Bufanda Rosa.

![captura del programa](img/shell.png)

<pre>
bufandarosa -c ayuda
</pre>


# Megabot

Un robot web pensado para ser lo mas generico posible.

<pre>
echo -e "pass 1234\nemail tuemail@mail.com\nstatus mi%20mensaje" | megabot m.facebook.com
</pre>

_Esto debería enviar un mensaje a "tu" muro de facebutt_

# Wgetpaste

intento manterner la ultima versión en el repo. [Sitio original](http://wgetpaste.zlin.dk/)
