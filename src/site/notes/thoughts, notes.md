---
{"dg-publish":true,"permalink":"/thoughts-notes/","pinned":true,"tags":["gardenEntry"],"created":"","updated":""}
---


## ..on people and knowledge work


![img](https://source.unsplash.com/collection/51177910){: style="float:right; width: 50%; max-width: 300px; max-height: 300px;  margin-left: 10px;"}

musings about how people work and how work work

a few notes
```dataview
LIST
FROM "notes"
WHERE dg-publish=true
LIMIT 7
```
a few observations[^1]

```dataview
LIST rows.file.link
FROM "observations"
WHERE dg-publish=true
SORT file.path DESC, file.name ASC
group by file.folder
```

[^1]: to observe - notice, take note of, make a remark about something (interesting)

<style>
.footer, .backlinks {
	display: none;
	visibility: none;
}

</style>