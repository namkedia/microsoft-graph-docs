---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ContactCollectionPage contacts = graphClient.me().contacts()
	.buildRequest()
	.get();

```