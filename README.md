# Soil Moisture Sensor

<img src="https://cdn-learn.adafruit.com/assets/assets/000/065/919/large1024/adafruit_products_4026_iso_demo_ORIG_2018_11.jpg?1542235880" alt="alt text" width="500">

I DD-Lab har vi det der hedder en Soil moisture sensor. Den kan bruges til at måle fugtigheden i jorden og sende data om hvor tørt eller fugtigt det er.

## Quickstart

**Følg adafruits detaljerede startup guide [her](https://learn.adafruit.com/adafruit-stemma-soil-sensor-i2c-capacitive-moisture-sensor/arduino-test)**

- Download "Adafruit_seesaw library" i arduino IDE

  ![](https://cdn-learn.adafruit.com/assets/assets/000/066/328/large1024/adafruit_products_image.png?1542825917)

- Kør "Adafruit seesaw Soil Sensor Example" for at teste om sensoren virker

  ![](https://cdn-learn.adafruit.com/assets/assets/000/066/330/large1024/adafruit_products_image.png?1542825980)

### Pin-out

<img src="https://cdn-learn.adafruit.com/assets/assets/000/066/338/large1024/adafruit_products_soilmetro.png?1542827941" alt="alt text" width="500">

- **GND** - power and logic ground
- **VIN** - 3-5V DC (use the same power voltage as you would for I2C logic)
- **I2C SDA** - there's a 10K pullup to VIN
- **I2C SCL** - there's a 10K pullup to VIN

## Selvvandende plante projekt

En måde hvorpå man kan anvende en soil-moisture sensor kunne eksempelvis være i et selvvandende plante system, hvor data fra soil moisture sensoren styre en lille vandpumpe. 

<img src="https://github.com/L4COUR/PlantWateringSystem/raw/master/media/Self-watering-system.gif" alt="alt text" width="500">

Se mere om hvordan man kan bruge soil moisture sensoren til at lave et selvandende plante anlæg [her](https://github.com/L4COUR/PlantWateringSystem). 

## sources:

- https://learn.adafruit.com/adafruit-stemma-soil-sensor-i2c-capacitive-moisture-sensor/overview
- https://github.com/L4COUR/PlantWateringSystem
