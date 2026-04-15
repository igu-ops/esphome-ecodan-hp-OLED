Testing to add OLED ssd1306 ATOM S3Lite to https://github.com/gekkekoe/esphome-ecodan-hp
Straight plugin via I2C G39/G38/VCC/GND and display sensor values
Use at your own risk
just add this to
packages:
  remote_package:
    oled:
    url: https://github.com/igu-ops/esphome-ecodan-hp-OLED/
    ref: main
    files:
      - OLED.yaml
