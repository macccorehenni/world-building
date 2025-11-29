---
title: Index by Topic
aliases: [Index by Topic]
---

# Index by Topic

```dataview
TABLE WITHOUT ID
  tag AS "Tag",
  rows.file.link AS "Files"
FLATTEN tags AS tag
WHERE tags
GROUP BY tag
SORT tag ASC
```
