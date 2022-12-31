---
layout: post
title:  "4CSCC weather monitoring at Townsite Urban Farm"
date:   2022-12-31
categories: announcements
---

Two Raspberry Pi Pico Ws have been deployed as prototypes at [Townsite Urban Farm (TUF)](https://townsite.farm) and are currently reporting Temperature, Pressure, and Humdity from two locations to the[Initial State](https://iot.app.initialstate.com/#/) IoT service.
The first location - *TUF hoophouse* - is inside the TUF "hoophouse" (a semi-permanent greenhouse), and the second location - *TUF chicken coop* - is outdoors, approximately 20 feet away mounted on the shed adjacent to the TUF chicken coop. Photos of the sites are below.

<iframe width="100%" height="600px" src="https://iot.app.initialstate.com/embed/#/tiles/bkt_h0i9l4mxsnqb"></iframe>

The full data dashboard can be accessed on [Initial State](https://go.init.st/xwi3scd).

<hr>

Our goal is to work with students in the Four Corners region to build a network of Raspberry Pi weather stations at schools.
Students will gain experience with hardware and software development for environmental monitoring, a first step in understanding and exploring the weather in their region.

Our next steps are solidifying the code deployed on the machines ([`4cscc-micropython`](https://github.com/4cscc/micropython-4cscc)), connecting hardware for monitoring wind speed, wind direction, and rain fall, and then working with students to scale up the operation.

Our biggest challenge in deployment will be Internet connectivity for sending data from our microcontrollers to the Internet, in areas with unreliable Internet connections.

<hr>

TUF hoophouse Pico (i.e., `tuf-1`):

![*TUF hoophouse* (hostname: `tuf-1`)](/images/2022-12-31-tuf-weather-station-images/tuf-1.png "*TUF hoophouse* (hostname: `tuf-1`)")

<hr>

TUF chicken coop Pico (i.e., `tuf-3`):

![*TUF chicken coop* (hostname: `tuf-3`)](/images/2022-12-31-tuf-weather-station-images/tuf-3.png "*TUF chicken coop* (hostname: `tuf-3`)")

<hr>

TUF chicken coop data sensors. The black cup houses the BME 280 temperature/humidity/air pressure sensor (we'll see if it holds up to weather), and the wind speed, wind direction, and rain gauge are mounted on the tall grey post.

![*TUF chicken coop sensors* (hostname: `tuf-3`)](/images/2022-12-31-tuf-weather-station-images/tuf-3-sensors.png "*TUF chicken coop sensors* (hostname: `tuf-3`)")

<hr>

The TUF site, indicating where sensors are located.

![*TUF site*](/images/2022-12-31-tuf-weather-station-images/tuf-site.png "*TUF site")

<hr>
