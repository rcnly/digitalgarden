---
{"dg-publish":true,"permalink":"/metrics/picking-performance/","dgHomeLink":true,"dgPassFrontmatter":false}
---


```dataviewjs
for (let page of dv.pages('#daily')) {
	if (page.file.name != 'DailyTemplate' && page.picked) {
		dv.header(2, page.file.name);
		dv.paragraph('![[' + page.file.name + '#Picking]]')
	}
}
```

