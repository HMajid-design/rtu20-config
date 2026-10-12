# RTU20 Config

Settings app for the RTU20 / RTU20-FLOW remote terminal unit (STM32G0 + u-blox SARA-R510S).

**Open it:** https://hmajid-design.github.io/rtu20-config/

- **Start demo** - a simulated RTU20 or RTU20-FLOW with the real settings list and factory values
  (direct link: https://hmajid-design.github.io/rtu20-config/#demo=RTU20-FLOW).
- **Connect USB** - Chrome or Edge on a PC: pick the RTU's USB serial port (115200 baud). The page talks
  the RTU's JSON settings API (`cfg.schema`, `cfg.get`, `cfg.set`) and builds its forms from the RTU.
- **API traffic** - every JSON request and reply, plus a box to send your own.
- **Export / Import** - settings as JSON (never the PIN or passwords).

Everything runs in the browser; nothing is sent anywhere except to the RTU on your USB port.
The page also works offline: download `index.html` and `demo-data.js` and open `index.html`.

This repository is published from `tools/rtu-config` of the (private) RTU20 firmware repository;
change it there and copy it here.
