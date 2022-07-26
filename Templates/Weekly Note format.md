---
tags: POV
title: Week 
---

# Week <% tp.date.now("WW",-119)%>

[Previous Week](<% tp.date.now("YYYY-[W]WW",)%>)
[Next Week](<% tp.date.now("YYYY-[W]WW",+14)%>)

# Events

```itinerary
slotLabelFormat: { hour: 'numeric', minute: '2-digit', omitZeroMinute: false, hour12: false }
headerToolbar: false
scrollTime: '08:00:00'
slotDuration: '02:00:00'
height: 300
initialDate: {{date:YYYY-MM-DD}}
initialView: timeGridWeek
```

## Day's Event

```itinerary-event
title: 
allDay: false
start: {{date:YYYY-MM-DD}}
end: {{date:YYYY-MM-DD}}
color: 
tag:
- 
```

