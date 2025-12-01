```dataview
TABLE WITHOUT ID
  tag AS "Tag",
  rows.file.link AS "Notes"
FLATTEN file.tags AS tag
WHERE file.tags
GROUP BY tag
SORT tag ASC
```
