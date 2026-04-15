Testing to add OLED ssd1306 ATOM S3Lite to https://github.com/gekkekoe/esphome-ecodan-hp<br/>
Straight plugin via I2C G39/G38/VCC/GND and display sensor values  
Use at your own risk<br/>
just add this to<br/>
packages:<br/>
  remote_package:<br/>
    oled:<br/>
    url: https://github.com/igu-ops/esphome-ecodan-hp-OLED/<br/>
    ref: main<br/>
    files:<br/>
      - OLED.yaml
