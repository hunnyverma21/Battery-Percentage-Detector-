# Battery Percentage Detector

A small HTML, CSS, and JavaScript project that reads the device battery level using the browser Battery Status API.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a supported browser.
3. If battery information is unavailable when opening the file directly, run it from a secure context such as `localhost` or HTTPS.

## Features
- Live battery percentage
- Charging / discharging status
- Battery level indicator with low-battery warning
- Charging and discharging time estimates when provided by the browser

## Browser support
The Battery Status API is not supported by every browser or device. The app displays a support message when the API is unavailable. It does not fabricate battery readings.
