---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var securityEnabledOnly = true;

await graphClient.Contacts["{orgContact-id}"]
	.GetMemberGroups(securityEnabledOnly)
	.Request()
	.PostAsync();

```