---
date: <% tp.date.now() %>
tags: [ ]
---

<%*
	const originalTitle = tp.file.title;
	const hashed = originalTitle + "_" + tp.date.now("YYYYMMDDHHmmss");
	await tp.file.rename(hashed);
%>