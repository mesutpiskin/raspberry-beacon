[English](./README.md) | Türkçe

<div align="center">

<img width="200" src="./static/logo.png"/>

<h1 align="center">Raspberry Pi ile in-House Beacon</h1>

</div>


### Beacon Teknolojisi

Beacons are small devices that use Bluetooth low-energy (BLE) wireless technology to pinpoint your location and serve content based on where you’re at.

Consider this: Smartphones differ from computers in that we typically carry them around with us everywhere we go. This creates opportunities for location-based advertising and other services.  This is beacon mobile technology at work, and it’s increasingly used by businesses in every industry since the Apple iBeacon was introduced in 2013. Retailers and restaurants use beacons to present coupons and promotions. Hotels use beacons to unlock doors. Beacons are used in professional sports arenas, airlines, trade shows, and more.


### Nasıl çalıştırırım?

- Projeyi indirin

```sh
git clone https://github.com/mesutpiskin/inhouse-beacon.git
```
- bağımlılıkları yükleyin
```sh
 pip install -r requirements.txt
 ```

- Mobil istemcilere bildirim gönderebilmek için scan_ble_devices.py dosyasındaki FIREBASE_API_KEY'i güncelleyin.
- Run this project

```sh
python scan_ble_devices.py
```
***Raspberry Pi 3B üzerinde Python 2.x kullanarak test edilmiştir***