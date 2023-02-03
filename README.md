# aisonobuoy-collector-pinephone
A PinePhone based maritime data collection system. Designed for continuous hydrophone audio, AIS, and other telemetry data collection for machine learning dataset creation.

This system is part of the IQT Labs [AI Sonobuoy](https://github.com/IQTLabs/AISonobuoy) project.

<img src="./hardware/media/pinephone-aisonobuoy-system.png" width="600  ">

## Software

This repo is under active developoment. The current required directory structure is below. You will need to clone the `edgetech` repos into your enviornment (they will be listed as sobmodules to this repo at the time of the first verson tag).

```
aisonobuoy-collector-pinephone
|-- docker-compose.yaml
|-- edgetech-core
|-- edgetech-daisy
|-- edgetech-filesaver
|-- edgetech-c2c
|-- edgetech-pinephone-telemetry
|-- edgetech-couchdb-saver
|-- edgetech-database-sync
|-- edgetech-audio-recorder
|-- edgetech-http-uploader
... IN PROGRESS
|-- edgetech-s3-uploader
```

To run `cd` into the `aisonobuoy-collector-pinephone` repo and run `docker-compose up --build`.

# Hardware

## BOM

- [Pine Phone Pro](https://pine64.com/product/pinephone-pro-explorer-edition/)
- [Seahorse SE58 Drybox](http://www.seahorsecases.com/seahorse-se58-micro-case-81-x-41-x-43.html)
- [Aquarian H2a Hydrophone](https://www.aquarianaudio.com/h2a-hydrophone.html)
- [Voltaic V50 USB Battery Pack](https://voltaicsystems.com/v50/)
- [Voltaic 9 Watt Solar Panel](https://voltaicsystems.com/9-watt-18v-panel-etfe/)
- [Voltaic Solar Panel Bracket](https://voltaicsystems.com/large-bracket/)
- [Right angle Female 3.5x1.1mm - MicroUSB](https://voltaicsystems.com/f3511-microusb/)
- [dAISy 2+ dual-channel AIS Receiver](https://shop.wegmatt.com/products/daisy-2-dual-channel-ais-receiver-with-nmea-0183)
- [Anker 543 USB-C Hub](https://www.anker.com/products/a8365?variant=37438670667926)
- [PG 13.5 Cable Gland](https://voltaicsystems.com/PG135)

## 3D Printed STL Files

- [Lid Phone Mount]()
- [Drybox component mount insert]()

## Assembly

<img src="./hardware/media/pinephone-aisonobuoy-system.gif" width="600  ">