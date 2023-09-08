# Habridge

Emulates Philips Hue API to other home automation gateways such as an Amazon Echo/Dot Gen 1 (gen 2 has issues discovering ha-bridge) or other systems that support Philips Hue. The Bridge handles basic commands such as 'On', 'Off' and 'brightness' commands of the hue protocol. This bridge can control most devices that have a distinct API. In the cases of systems that require authorization and/or have APIs that cannot be handled in the current method, a module may need to be built. The Harmony Hub is such a module and so is the Nest module. The Bridge has helpers to build devices for the gateway for the Logitech Harmony Hub, Vera, Vera Lite or Vera Edge, Nest, Somfy Tahoma, Home Assistant, Domoticz, MQTT, HAL, Fibaro, HomeWizard, LIFX, OpenHAB, FHEM, Broadlink and the ability to proxy all of your real Hue bridges behind this bridge. This bridge was built to help put the Internet of Things together. For more information about how to use this software have a look at their Wiki https://github. Com/bwssytems/ha-bridge/wiki

---

**Homepage:** https://hub.docker.com/r/linuxserver/habridge

**WebUI Port:** `8080`