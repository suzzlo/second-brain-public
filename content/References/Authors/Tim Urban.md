---
tags:
  - author
sticker: lucide//person-standing
---
## Biography

## Books

```dataview
Table datePublished.year as Published, avgRating as Rating, status as Status
from #book 
where contains(author, this.file.name)
```

## Blog

## Talks

```dataview
Table datePublished.year as Published, avgRating as Rating, status as Status
from #talk
where contains(author, this.file.name)
```