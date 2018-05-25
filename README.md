Entramos al direcctorio donde tenemos el DMRIds.dat:
cd /usr/local/etc/

Bajamos el fichero:
git clone https://github.com/ea4gax/DMRIds2.dat

Le damos permisos:
rpi-rw
chmod 755 /usr/local/etc/DMRIds2.dat

Cambiaremos la ruta del fichero en la configuración del ini entrando en modo expert. Pinchamos en MMDVMHost y vamos a la línea RSSIMappingFile y le pondremos esta ruta: /usr/local/etc/RSSI2.dat
