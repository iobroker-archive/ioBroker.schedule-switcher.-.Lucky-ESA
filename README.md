![Logo](admin/schedule-switcher.png)

# ioBroker.schedule-switcher

[![NPM version](https://img.shields.io/npm/v/iobroker.schedule-switcher.svg)](https://www.npmjs.com/package/iobroker.schedule-switcher)
[![Downloads](https://img.shields.io/npm/dm/iobroker.schedule-switcher.svg)](https://www.npmjs.com/package/iobroker.schedule-switcher)
![Number of Installations](https://iobroker.live/badges/schedule-switcher-installed.svg)
![Current version in stable repository](https://iobroker.live/badges/schedule-switcher-stable.svg)

[![NPM](https://nodei.co/npm/iobroker.schedule-switcher.png?downloads=true)](https://nodei.co/npm/iobroker.schedule-switcher/)

**Tests:** [![Test and Release](https://github.com/Lucky-ESA/ioBroker.schedule-switcher/actions/workflows/test-and-release.yml/badge.svg)](https://github.com/Lucky-ESA/ioBroker.schedule-switcher/actions/workflows/test-and-release.yml)

## schedule-switcher adapter for ioBroker

This adapter allows the user to switch devices on/off or 100/0 using time schedules.
The schedules can be fully configured by a vis or vis-2 widget.
One schedule switches one or more ioBroker states and consists of one or more triggers that define when and how the state should be switched.
It is possible to configure at which time and on which weekdays the trigger should be triggered. Astro triggers or countdowns can also be created.

## Requirements

-   Node 18
-   JS-Controller >= 6.0.11
-   Admin >= 7.0.23
-   VIS or VIS-2

## Description

🇬🇧 [Description](/docs/en/README.md)</br>
🇩🇪 [Beschreibung](/docs/de/README.md)

## Questions

🇩🇪 [Fragen](https://forum.iobroker.net/topic/77552/test-adapter-schedule-switcher)

## Changelog

<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->

### 0.0.1 (2024-10-19)

-   (Lucky_ESA) initial release

## License

MIT License

Copyright (c) 2024 Lucky_ESA <github@luckyskills.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
