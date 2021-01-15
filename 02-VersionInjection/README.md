
# What is OTAdrive

## Introduction

There are many companies that produce products based on hardwares such as ESP8266, RaspberryPi, STM32 microcintrollers etc. Main problem to produce this products is firmware bugs! If there were any bug about formware, company doesn't access to customer to update product's firmware. By the way upgrading firmwares usually need technical knowlegde and programmer where customer doesn't have any of these.

[OTA drive](http://www.otadrive.com) is here to help solve this problem. Today we support ESP8266 and you can upgrade your ESP8266 based product without any server developing.

![OTAdrive](/documents/img/loop.jpg)

## Features

* Full list of your devices
* Grouping devices and control versioning of each device group separately
* Monitor device activities
* Monitor device upgrades
* Block unwanted devices to access OTA
* Json configuration for device

# Getting Started

This project is a simple blinker test. You can upgrade this blinker easily via OTAdrive dashboard.

![OTAdrive](/documents/img/esploop.jpg)


## How to build

Each product has an unique key to access upgrade API. You should replace [00000000-0000-0000-0000-000000000000] with your own key. Find key in API section of your product in [OTA drive](http://www.otadrive.com).

## Toturial Video

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TnZph-ftoWo/0.jpg)](https://www.youtube.com/embed/TnZph-ftoWo)