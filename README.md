
# Tron-Identity-Disks

This software manages a Tron Identity Disk running on a ESP32 or ESP8266. The goal is for the code to be able to manage all the componenets with different modes and cool effects. This repository will focus mostly on the code starting out and then on the hardware later in the process. Designs for Tron Legacy &amp; Ares should be the final goal!

## Features
I will split the features into diffrent sections since the disk will have two different modes at first and maybe more later down the road.

 #### Main
- [ ] Smooth Neopixel control.
- [ ] Manual control using buttons or capacitive sensors.
- [ ] Battery indicator & low battery warning.
- [ ] OTA updates.
- [ ] Power limits managed mainly by smart brightness control.
- [ ] Test mode for testing max power draw.

 #### Light Mode
 In this mode the identity disk will act like a smart light.
- [ ] MQTT & Home Assistant support! 
- [ ] Matter support?
- [ ] Animations.
- [ ] Clock mode for showing time using leds.
- [ ] Ambient light sensor for auto brightness.

#### Disk mode
In this mode the identity disk will act more like a real identity disk.
- [ ] NeoPixel animations during sudden acceleration/deaccelearation.
- [ ] Realistic sounds based on movement.
- [ ] Battery optimization.


## License

To support the sustainability of our project, we have chosen to release our software under the Fair Source License. This ensures that the software remains free for personal use while maintaining full transparency of the code. It also protects our work from being used by competitors without contributing to its upkeep or providing support to end users. For full details, please see the LICENSE file.

If your intended use falls outside the terms of this license and you require a separate agreement, please contact me at andreas.kb@icloud.com
 for further information.


 ---------------------------------------

 ## Research
 - [Fastled](https://github.com/FastLED/FastLED) for neopixel lights management.
 - [WifiManager] with modifications for wifi and credentials.
