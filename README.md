Entramos al direcctorio donde tenemos el DMRIds.dat:
cd /usr/local/etc/
Nos ponemos en modo escritura:
rpi-rw

Bajamos el fichero:
sudo git clone https://github.com/ea4gax/DMRIds2git
Nos bajar una carpeta llamada DMRIds2
Le damos permisos:
chmod 755 /usr/local/etc/DMRIds2.dat

Cambiaremos la ruta del fichero en la configuración del ini entrando en modo expert. Pinchamos en MMDVMHost y vamos al apartado
DMR Id Lookup y le pondremos esta ruta: /usr/local/etc/RSSI2.dat
