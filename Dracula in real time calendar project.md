---
tags: 
title: Dracula in real time calendar project
---

## Templater
Tomorrow:  `[[<% tp.date.now("YYYY-MM-DD", 1) %>]]`

## Periodic Notes

https://github.com/liamcain/obsidian-periodic-notes#setting-up-your-first-calendar-set

## Itinerary Plugin

#### Character Itinerary Colors

Jonathan: Navy

Mina: DarkGreen

Holmwood: MediumPurple

Seward: DeepSkyBlue

Quincey: SandyBrown

Lucy: Crimson

Captain: Gray

https://github.com/coddingtonbear/obsidian-itinerary

Template:

v ONLY SHOWS ITINERARY FOR CURRENT WEEK

```itinerary
slotLabelFormat: { hour: 'numeric', minute: '2-digit', omitZeroMinute: false, hour12: false }
headerToolbar: False
scrollTime: '08:00:00'
slotDuration: '01:00:00'
height: 200
allDaySlot: false
initialdate: 
initialView: listWeek
```

### Calendar View

https://fullcalendar.io/docs/timegrid-view

https://fullcalendar.io/docs/daygrid-view

```itinerary
initialDate: 2021-11-01
headerToolbar: false

```

#### Event Syntax

https://fullcalendar.io/docs/event-parsing

###### Hotel

```itinerary-event
title: Hotel Fortin Plaza
start: 2021-10-31T17:00
end: 2021-11-04T11:00
color: brown
tag:
- hotel
```

**Hotel Fortin Plaza**

Address: Venus 118, Estrella, 68040 Oaxaca de Juárez, Oax., Mexico

Phone: : +52 951 515 7777

_![:pleadcry:](https://cdn.discordapp.com/emojis/802002483152289822.gif?size=44&quality=lossless)_