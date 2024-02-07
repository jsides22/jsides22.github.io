---
description: "Repairing and redesigning instrumentation on Electrathon racecar"
paige:
  style: |
    #paige-collections,
    #paige-sections,
    #paige-reading-time,
    #paige-date,
    #paige-credit,
    #paige-pages {
        display: none;
    }
    #paige-title {
        font-size: 3rem;
    }
title: "Electrathon Car"
---

{{< paige/image
sizes=""
src="/assets/electrathon_car_full.jpg"
style="float:left; max-width: 100%; margin-right: 20px; margin-bottom: 20px;"
width="50%" >}}
{{< paige/image
sizes=""
src="/assets/electrathon_instrumentation.jpg"
style="float:left; max-width: 100%; margin-right: 20px; margin-bottom: 20px;"
width="50%" >}}

**Project overview:** 
Electrathon is a racing event that involves creating the most efficient racecar possible. The goal of the event is to complete as many laps as possible within one hour while only being supplied with 1 kWh of power. At George Fox, there is a team of about 5 people that work on the car. My goal of the project is to repair and redesign the driver's instrumentation. The instrument panel needs to display 4 main things: estimated time left before batteries die, current speed, battery voltage, and temperatures. The instrumentation is controlled by an Arduino Mega through an I2C interface. For my redesign, I designed and modeled a new instrument pod and faceplate for the LCDs to sit in, and replaced the Arduino Nano that was controlling the RGB lights to indicate temperatures. This project is still underway, so the housing for the LCDs is not finished yet.