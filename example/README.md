# GeoClue for Dart examples

- [simple.dart](https://github.com/jpnurmi/geoclue.dart/blob/main/example/simple.dart)

  A minimal example to get the current location and listen to location updates.

- [example.dart](https://github.com/jpnurmi/geoclue.dart/blob/main/example/example.dart)

  A simple _Where Am I?_ example using GeoClue. Basic functionality:

  1. Create a `GeoClueManager` and connect to the GeoClue D-Bus service running in your machine.
  2. Use a `GeoClueClient` to set the desired properties and obtain the `GeoClueLocation` provided by the service.