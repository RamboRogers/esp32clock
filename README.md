![screenview](screenview.png)

I yearned for the feeling of the 90s in a bedside clock, but the tech of today.  The softness and hardness of the legacy LED displays. I also brought in a few personal requirements.


- The time should always be right.
- I want to be notified if a car, person, or animal is in my backyard or frontyard at night.
- I wanted it to show the current weather as soon as I wake up so I know if I want to go out on my deck and how I will dress for the day. 
- This helps me answer my wife "is it hot in here or is it me", now I can answer the temperature as a fact for her queries.

This 3D print snaps together quite well, the screen and sensors stay in place because of friction. I down sized the hole by .03mm so you have to snug them in, but they stay!  

If anyone makes one of these I'd love to see it. ( [https://github.com/RamboRogers/esp32clock](https://github.com/RamboRogers/esp32clock) )

https://blog.matthewrogers.org/

# License

GNU GPLv3

## Features

- Vintage 90s feeling with this textual LCD display
- Wifi Connectivity
	- Auto updates time on boot via NTP
	- Weather updated from National Weather service API based upon GEO location
	- Online status indicator for your internet (powered by [HomeAssistant](https://www.home-assistant.io/))
	- Instant alarms and automations from [HomeAssistant](https://www.home-assistant.io/)
	- Local temperature information
- Ability to easily customize content on screen.
- [ESP32Home](https://esphome.io/) based so can be configured via YAML and updated via Wifi
- Low power usage.

## Parts


| **Screen**         | [https://www.amazon.com/gp/product/B0C1G9GBRZ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1](https://www.amazon.com/gp/product/B0C1G9GBRZ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)   |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Buzzer**         | [https://www.amazon.com/gp/product/B07GBTJP9F/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1](https://www.amazon.com/gp/product/B07GBTJP9F/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) |
| **ESP32**          | [https://www.amazon.com/gp/product/B08D5ZD528/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1](https://www.amazon.com/gp/product/B08D5ZD528/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)   |
| **Temp Sensor**    | [https://www.amazon.com/gp/product/B0BTVW39R2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1](https://www.amazon.com/gp/product/B0BTVW39R2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) |
| **3D Print File**  | [https://github.com/RamboRogers/esp32clock](https://github.com/RamboRogers/esp32clock)                                                                                                       |
| **ESPHome Config** | [https://github.com/RamboRogers/esp32clock](https://github.com/RamboRogers/esp32clock)                                                                                                       |
