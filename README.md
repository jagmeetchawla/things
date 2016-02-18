# Synopsis
DIY IOT Library for Raspberry Pi
- Python library (ThingsPy) for
  - Defining your own RESTFul API and Controller for asynchronously controlling "things" connected to Rapsberry Pi GPIO.
  - RPi.GPIO / WiringPi wrapper with "mocks" for development on your own Mac
  - "things" registration and discovery
  - "things" plugin - the actual piece of code that will control your own "thing" connected to Raspberry Pi.
  - "things" status - ephemeral/persistent data store
  - "things" log persistance/archive
  - "things" talking to "network" via a chatty protocol
  - "things" uploading / offloading state, data, logs to cloud or your own database

- Swift SDK (SwiftThingsPy) for invoking ThingsPy RESTFul API
- Mac/iOS Viewer Apps for "things"
- Mac/iOS Simulator App for "things"

What about:
- Queue?
- Errors?

# Motivation

Just started with my own DIY home automation project. Doing this to make my own life easier by removing all the boilerplate away.
