---
date: <% tp.date.now() %>
Project:
---

<%*
	const originalTitle = tp.file.title;
	const hashed = originalTitle + "_" + tp.date.now("YYYYMMDDHHmmss");
	await tp.file.rename(hashed);
%>