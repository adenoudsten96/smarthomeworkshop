# Smart Home Workshop Capita Selecta

Dit is de tutorial voor de smart home workshop die tijdens het seminar gegeven wordt. In deze repository vindt je een stap-voor-stap uitleg voor het aansluiten van de DHT11 sensor aan Home Assistant op een Raspberry Pi. Tevens staan hier ook alle complete `.yaml` files in.

Je hebt als het goed is een setje met spullen gekregen. Check of je alles hebt:

- 1x Raspberry Pi 3B
- 1x DHT11 sensor
- 1x 4.7K weerstand
- 1x breadboard
- 4x kabels

### Stap 1: Aansluiten DHT sensor

Voordat je de Pi aan zet gaan we eerst de DHT11 sensor aansluiten. Doe dit als volgt:

- Sensor Pin 1 -> Raspberry Pi pin 1 (3.3V)
- Sensor Pin 2 -> Raspberry Pi pin 7 (GPIO 4)
- Sensor Pin 3  gebruiken we niet.
- Sensor Pin 4 -> Raspberry Pi pin 6 (Ground)

Let op dat je de oriëntatie van de DHT11 goed hebt. Gebruik onderstaande diagrammen als hulpmiddel.

![Aansluiting](aansluiting.jpg)

![GPIO pins](gpio.jpg)

### Stap 2: Verbinden Home Assistant

- opstarten pi
- navigeren naar ip adres browser

### Stap 3: Koppelen DHT sensor Home Assistant

- inloggen met SSH
- kopieren YAML
- reboot?
- terug naar dashboard

### Stap 4: Automation maken

- stappen doorlopen dashboard
- json plakken

