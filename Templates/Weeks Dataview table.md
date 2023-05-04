
# Dataview

```dataview
table without ID
link(file.name, string(date(file.link))) as "Date", file.etags as "POV"
FROM outgoing([[<%tp.file.title%>]]) AND #Entry
```
