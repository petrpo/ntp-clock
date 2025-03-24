# NTP clock
- small esp project 
- esp will connect via WiFi & will get the time from NTP
- It will show the time on the display

Parts for the project
- esp8266      - version NodeMCU
- OLED display - 0.91" 128x32 OLED displej, I2C 
- 4 jumpers

Connections
- NodeMCU VCC,GND - OLED VCC, GND
- NodeMCU PIN D1  - OLED SCL
- NodeMCU PIN D2  - OLED SDA
