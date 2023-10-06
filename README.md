# zigbee-power-counter
electricity consumption counter using the flashing LED on the electricity meter. It uses a zigbee network, a PCF8583 circuit and an E18MS1PA2 radio module


schema 1:

![pcf8583-counter](https://github.com/halata83/zigbee-power-counter/assets/25054422/f04ffc6f-8562-4ae5-a260-ff628fd30756)

schema 2:

![counter](https://github.com/halata83/zigbee-power-counter/assets/25054422/b564d098-5ca8-4df4-85a2-b89cebff659b)

používám schema 1 a funguje to
74HC132 slouží k uprave vstupniho signálu aby to mělo pekne hrany
Firmware se vytvoří pomocí ptvo.info configurable firmware sw: https://ptvo.info/download/ptvo-firmware-latest.zip

a nastaví podle techto obrázku:
 

![ptvo1](https://github.com/halata83/zigbee-power-counter/assets/25054422/ddb605e8-6f06-4547-b815-6740a7182af0)


![ptvo2](https://github.com/halata83/zigbee-power-counter/assets/25054422/2dcf325b-fe0b-474e-b775-64f80c1721fd)


celé zapojeni a nastaveni pocházi od:
https://github.com/Mr-Groch/PTVO-Zigbee-CC2530-PCF8583-counter

címž mu děkuji
