---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let decisions = await client.api('/accessReviews/2b83cc42-09db-46f6-8c6e-16fec466a82d/decisions')
	.version('beta')
	.get();

```