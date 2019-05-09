English | [Türkçe](./README.tr-TR.md)

<div align="center">

<img width="200" src="./static/logo.png"/>

<h1 align="center">in-House Beacon Project with Raspberry Pi 3</h1>

</div>


### Beacon Technology

Beacons are small devices that use Bluetooth low-energy (BLE) wireless technology to pinpoint your location and serve content based on where you’re at.

Consider this: Smartphones differ from computers in that we typically carry them around with us everywhere we go. This creates opportunities for location-based advertising and other services.  This is beacon mobile technology at work, and it’s increasingly used by businesses in every industry since the Apple iBeacon was introduced in 2013. Retailers and restaurants use beacons to present coupons and promotions. Hotels use beacons to unlock doors. Beacons are used in professional sports arenas, airlines, trade shows, and more.



### Hot to Run?

- Download or clone project

```sh
git clone https://github.com/mesutpiskin/inhouse-beacon.git
```
- install  requirements
```sh
 pip install -r requirements.txt
 ```

- Update FIREBASE_API_KEY in scan_ble_devices.py file for mobile client notification.
- Run this project

```sh
python scan_ble_devices.py
```
***Tested on Python 2.x on Raspberry Pi 3B***