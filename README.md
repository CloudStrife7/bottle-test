# bottle-test

A one-page test that reads a HidrateSpark smart bottle over Web Bluetooth, with no app.
Open `index.html` through https (GitHub Pages), tap Connect, pick the bottle. It lists the bottle's
services, reads battery and model, and prints each sip as raw bytes and as a percent of the bottle.

- It only listens. It writes to the bottle only when you press the two write buttons.
- Needs Chrome, or Brave with the Web Bluetooth flags on. Close the HidrateSpark app first (the bottle
  accepts one connection).
- Protocol notes come from [agua_amiga](https://github.com/mpnordland/agua_amiga) (MIT) and
  [HA-HidrateSpark-Bluetooth-Proxy](https://github.com/loryanstrant/HA-HidrateSpark-Bluetooth-Proxy) (MIT).
