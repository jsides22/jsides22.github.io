---
description: "Sophomore Digital Logic project"
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
title: "FPGA Simon Project"
---

{{< paige/image
sizes=""
src="/assets/simon.png"
style="float:left; max-width: 100%; margin-right: 20px; margin-bottom: 20px;"
width="50%" >}}

**Project overview:** <br>
The Simon project is the final project for the Digital Logic Design class, which is a class for Sophomore computer and electrical engineering students. Simon is an electronic game of short-term memory skill. The goal of the game is to memorize the order that the buttons light up and then repeat the button inputs by memory. Each time you complete a round, the game repeats, but with one more light in the order each time. 

The goal of this project was to create a functional prototype from start to finish with only rough design requirements, like what would be given by a customer. The project was a two-person project. The design requirements that we were given had several features to implement into the device. These features were things such as a functional menu system, score keeping, pseudo-random lighting order, several "cheat modes" for testing, and, of course, the game itself. The project combines FPGA programming in Verilog, finite state machines, clock timing, and hardware control into one large project.