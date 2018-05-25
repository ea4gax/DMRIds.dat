Entramos al direcctorio donde tenemos el DMRIds.dat: <br>
cd /usr/local/etc/ <br>
Nos ponemos en modo escritura: rpi-rw <br>

Bajamos la carpeta: <br>
sudo git clone https://github.com/ea4gax/DMRIds2.git <br>
Nos bajará una carpeta llamada DMRIds2. <br>

Borramnos el fichero README.md ya que no nos hará falta: <br>
sudo chmod 777 /usr/local/etc/DMRIds2/README.md <br>
sudo rm -r /usr/local/etc/DMRIds2/README.md <br>

Cambiaremos la ruta del fichero DMRIds.dat en la configuración del ini entrando en modo expert. Pinchamos en MMDVMHost y vamos al apartado DMR Id Lookup y le pondremos esta ruta: /usr/local/etc/DMRIds2/DMRIds2.dat
