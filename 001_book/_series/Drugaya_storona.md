---
layout: default
title: "другая сторона"
description: "description"
---



```dataview
list
where contains(file.outlinks, this.file.link)
sort file.name
```

