# PlantBox

[![GitHub license](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/eveldee0680/PlantBox/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/eveldee0680/PlantBox.svg)](https://github.com/eveldee0680/PlantBox/issues)

PlantBox allow people to manage plants in a new way,
it respond the following problems:

- You lack of time
- You are absent
- You have lot of plants

## Table of content

- [Table of content](#table-of-content)
- [Introduction](#introduction)
    - [Server](#server)
    - [Client](#client)
- [Current progress](#current-progress)
- [Features](#features)
- [Contributing](#contributing)
- [Copyright and licence](#copyright-and-licence)

## Introduction

PlantBox is a school project which goal is to create a solution to plant management.
It contains two parts:

- A server which collect information and manage the plant
- A client that display the evolution of the plants or alert the user when needed  

All is written in C# with .Net Standard, .Net Core and Xamarin.

### Server

The server is a Raspberry Pi with appropriates captors:

- Humidity sensor
- Light sensor
- Temperature sensor

All input is read with [Unosquare library](https://github.com/unosquare/raspberryio).

### Client

The client is a mobile application made with [Xamarin.Forms](https://github.com/xamarin/Xamarin.Forms) for Android or iOS.

## Current progress

The project is at its very beginning, the protocol need to be written and no
hardware is ready.  
As a consequence, we won't accept issues or pull requests at the moment

Tasks list:

- Protocol
    - [ ] Documentation
    - [ ] Shared library
- Server
    - [ ] Getting information from captors
    - [ ] Communication with Client
- Client
    - [ ] Interface
    - [ ] Communicate with Server

## Features

Features that will be implemented still need to be decided, but here is a potential list:

- Water the plant
- Check light level
- Check temperature
- Alert the user when needed
- Display plants evolution on graphics

## Contributing

Contributions are disabled for the moment, see [Current progress](#current-progress)

## Copyright and licence

*PlantBox* is licensed under the [Mit Licence](https://github.com/eveldee0680/PlantBox/blob/master/LICENSE)

*[RaspberryIO](https://github.com/unosquare/raspberryio)* is licensed under the [Mit License](https://github.com/unosquare/raspberryio/blob/master/LICENSE)

*[MessagePack](https://github.com/neuecc/MessagePack-CSharp)* is licensed under the [Mit Licence](https://github.com/neuecc/MessagePack-CSharp/blob/master/LICENSE)
