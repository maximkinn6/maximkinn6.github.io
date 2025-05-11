---
layout: default
title: "другая сторона"
description: "description"
---



table file.ctime as "Создано"
where contains(file.outlinks, this.file.link)
sort file.ctime desc