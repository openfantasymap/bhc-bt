# bhc-bt

A single-page **Web Bluetooth** console for talking to the *Beyond Humanity: Colonies* electronic core ("ARC") over BLE.

**Live tool:** https://openfantasymap.github.io/bhc-bt/

It connects over the Nordic UART Service, builds/parses the framed serial protocol (start byte, length, CRC‑8), and gives you one-click commands plus a custom-frame sender and a session log you can export.

## Usage

Open the live link in **Chrome / Edge** (desktop or Android) on a device with Bluetooth, near a powered-on ARC, then click **Connect**.

> Web Bluetooth requires a secure context (HTTPS or `localhost`) and a Chromium-based browser. To run locally: `python3 -m http.server` and open `http://localhost:8000/`.

## Status

Experimental / community interoperability tool. Not affiliated with or endorsed by the game's publisher.
