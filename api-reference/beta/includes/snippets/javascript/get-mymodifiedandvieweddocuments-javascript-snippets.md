---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let used = await client.api('/me/insights/used')
	.version('beta')
	.orderby('LastUsed/LastAccessedDateTime desc')
	.get();

```