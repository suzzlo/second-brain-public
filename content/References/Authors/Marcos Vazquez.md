---
sticker: lucide//person-standing
tags:
  - author
---
## Books

```dataview
Table datePublished.year as Published, avgRating as Rating, status as Status
from #book 
where contains(author, this.file.name)
```

## Podcasts

## Articles

