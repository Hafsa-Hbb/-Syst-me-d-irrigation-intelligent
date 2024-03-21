# -Syst-me-d-irrigation-intelligent
Dans ce système d’irrigation, divers capteurs tels que capteur d'humidité de
sol, le capteur DHT22, capteur de détection de pluie sont connectés aux
broches d'entrée d’ESP8266. Qui agit comme un cerveau pour l'ensemble du
système. Les valeurs détectées par les capteurs sont affichées sur l'écran de
l’afficheur OLED et seront transférées aux actionneurs pour agir sur ces
données. Si la valeur détectée dépasse les valeurs de seuil définies dans le
programme, la pompe sera automatiquement activée/désactivée par le circuit
de relais. L'ESP8266 enregistre également les données d'humidité du sol et
de pluie ainsi que les données de capteur DHT22 dans le cloud Thingspeak.
Les mêmes données sont également acquises et affichées dans l'application
Blynk
