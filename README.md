# OpenUSBShield
anyone know of or want to start an open source project for creating USB C type voltage sniffer for bad USB/cables,
similar to:
https://shop.hak5.org/products/malicious-cable-detector-by-o-mg
 but not so much a money grab
Hak5
Malicious Cable Detector by O.MG
The Malicious Cable Detector allows you to detect all known malicious USB cables, even the extremely stealthy O.MG Cables! Additionally, the Detector functions as a data blocker for safe charging. It is easy to use: plug just the cable into the Detector, then plug the Detector into your computer's USB port. LED activit
Image
Skippy
 — 
Today at 10:08 AM
idealistically, it would have 
pd voltage logic pass through, 
data disconnect switch
wifi/rfid sniffer
price point of like $10 or $20
optional DIY

Absolutely, here's a markdown requirements document for both the standard and pro versions of your device:

# USB-C PD Passthrough Device Requirements

## Standard Version

1. **USB-C Power Delivery (PD) Passthrough:** The device should allow power to be delivered through it according to the USB-C PD standard. This means it needs to handle voltages up to 20V and currents up to 5A, depending on the power level negotiated by the devices.

2. **Power Monitoring:** The device should be able to read the power coming in. This will likely involve measuring both the voltage and the current.

3. **Data Line Control:** The device should be able to disable and enable the data lines when directed by the user. This will allow the user to control whether data can be transferred through the device.

4. **LED Status Indicators:** The device should have LED status lights for different states:
   - Standby: Blue
   - Safe: Green
   - Unsafe: Red
   - Unsure: Orange

## Pro Version

All features of the Standard Version, plus:

1. **Voltage Logging:** The device should periodically log the voltage level. This data should be stored in non-volatile memory and should be retrievable by the user.

2. **Voltmeter:** The device should include a voltmeter for more precise measurement of the voltage.

3. **OLED Display:** The device should include a small OLED display. This display should show the current voltage and, if possible, a graph of the voltage over time.
