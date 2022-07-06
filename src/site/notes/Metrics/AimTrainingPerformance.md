---
{"dg-publish":true,"permalink":"/metrics/aim-training-performance/","dgHomeLink":true,"dgPassFrontmatter":false}
---


```dataviewjs
for (let page of dv.pages('#daily')) {
	if (page.file.name != 'DailyTemplate' && page.aimtrained) {
		dv.header(2, page.file.name);
		dv.paragraph('![[' + page.file.name + '#Aim Training]]')
	}
}
```

