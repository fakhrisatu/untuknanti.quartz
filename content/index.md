---
title: Welcome to Quartz
publish: "true"
modified: 2026-09-16T20:46:24+08:00
---

This is a blank Quartz installation.
See the [documentation](https://quartz.jzhao.xyz) for how to get started.

```dataview
TABLE 
    file.ctime AS "Created"
WHERE row["dg-publish"] = true
SORT file.ctime DESC
LIMIT 10
```
