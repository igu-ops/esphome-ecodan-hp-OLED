<h2>OLED SSD1306 Support for ATOM S3 Lite</h2>

<p>
Testing integration of an OLED SSD1306 display with the ATOM S3 Lite for:<br>
<a href="https://github.com/gekkekoe/esphome-ecodan-hp">
https://github.com/gekkekoe/esphome-ecodan-hp
</a>
</p>

<h3>Setup</h3>

<p>
Connect the OLED via I2C:<br>
G39 → SDA<br>
G38 → SCL<br>
VCC → Power<br>
GND → Ground
</p>

<p><strong>Use at your own risk!</strong></p>

<hr>

<h3>Configuration</h3>

<p>Add the following to your ESPHome configuration:</p>

<pre>
packages:
  remote_package:
    oled:
      url: https://github.com/igu-ops/esphome-ecodan-hp-OLED/
      ref: main
      files:
        - OLED.yaml
</pre>
