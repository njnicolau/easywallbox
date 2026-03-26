# easywallbox
Código de ESPHOME para controlar un cargador easywallbox de esolution

Con la ayuda de Claude he desarrollado este código para poder comandar un cargador easywallbox desde Home Assistant mediante una ESP32.

El código está en desarrollo, de momento solo permite parar la carga desde la aplicación, aún no consigo obtener datos.

Para probarlo tendreís que substituir con la MAC de vuestro cargador y el PIN que está en el código QR del cargador. En el archivo ejemplo.secrets.yaml pongo los datos que hacen falta
_________________

ESPHome code to control an eSolutions EasyWallbox charger

With the help of Claude, I have developed this code to command an EasyWallbox charger from Home Assistant using an ESP32.

The code is currently under development; for now, it only allows stopping the charging process from the app, and I haven't managed to retrieve data yet.

To test it, you will need to replace the MAC address with your charger's address and the PIN found on the charger's QR code. I have included the required fields in the example.secrets.yaml file.
