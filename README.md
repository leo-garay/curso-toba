## Instalar Toba

git clone https://github.com/SIU-Toba/template-proyecto-toba

mv template-proyecto-toba toba_vendor

dentro del contenedor 
cd /app/toba
composer install

 export TOBA_INSTALACION_DIR=/app/instalacion   
 cd /app/toba/bin

 ./toba instalacion instalar
 ./toba instalacion cambiar_permisos
