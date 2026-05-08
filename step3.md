```bash
touch /home/usuario/datos-locales/backup1.sql /home/usuario/datoslocales/foto_producto.jpg
nano migrar.sh
ENDPOINT="http://localhost:9000"
 BUCKET="s3://techlogistics-assets"
 LOCAL_DIR="/home/usuario/datos-locales"
 echo "Iniciando migración a la nube..."
 aws --endpoint-url $ENDPOINT s3 sync $LOCAL_DIR $BUCKET
 echo "Migración completada
chmod +x migrar.sh
./migrar.sh
