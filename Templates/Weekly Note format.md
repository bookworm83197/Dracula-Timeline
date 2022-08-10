---
tags: POV
title: 'Week <% tp.date.now("WW",-112)%>'
---

# Week <% tp.date.now("WW",-112)%>

[Previous Week](<% tp.date.now("YYYY-[W]WW",+7)%>)

[Next Week](<% tp.date.now("YYYY-[W]WW",+21)%>)

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

## [<%tp.date.now("MMMM D",1)%>](<% tp.date.now("YYYY-MM-DD", 1) %>)

```itinerary-event
title: 
allDay: true
start: {{date:YYYY-MM-DD}}
end: {{date:YYYY-MM-DD}}
color: 
tag:
- 
```

