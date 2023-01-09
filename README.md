# aisonobuoy-collector-pinephone
A PinePhone based maritime data collection system

This repo is under active developoment. The current required directory structure is below. You will need to clone the `edgetech` repos into your enviornment (they will be listed as sobmodules to this repo at the time of the first verson tag).

```
aisonobuoy-collector-pinephone
|-- docker-compose.yaml
|-- edgetech-core
|-- edgetech-daisy
... IN PROGRESS
|-- edgetech-filesaver
|-- edgetech-pinephone-telemetry
|-- edgetech-couchdb
|-- edgetech-s3-uploader
```

To run `cd` into the `aisonobuoy-collector-pinephone` repo and run `docker-compose up --build`.