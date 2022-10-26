---
title: "Defcon Aerospace Vilage - Hacking Satellites"
date: 2020-08-08T18:57:00+02:00
draft: false
catagories:
- Journal
tags:
- journal 
- hacking
- satellites
---
One good thing came out of Covid19 and that was that Defcon was run online in 2020 which meant that Pi and I got to attend. 

Since I have a particualr interest in space, satellites and radio, we spent a good portion of the weekend working on the satellite hacking challenge, which we eventually completed. Below are my final commands that were sent to the satellite.

```
!cmd login unakarlsen password
!cmd login admin 5p4c3d07c0m


!cmd ant calc -33 19 10
!cmd ant set sec 130
!cmd ant set pri 130


!cmd temp set 50 100

!cmd bat disable pri
!cmd bat disable sec

!cmd orbit mode man

!cmd orbit set inclination 180
!cmd orbit set eccentricity 3

!cmd orbit ignite
```
