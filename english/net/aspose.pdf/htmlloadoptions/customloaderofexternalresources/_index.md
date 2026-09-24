---
title: "HtmlLoadOptions.CustomLoaderOfExternalResources"
linktitle: "CustomLoaderOfExternalResources"
articleTitle: "CustomLoaderOfExternalResources"
second_title: "Aspose.PDF for .NET"
description: "Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resou..."
type: docs
weight: 130
url: "/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/"
product_version: "26.9.0"
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes)
 and supply custom method that will get requested resources from somewhere. For example, during usage 
 of Aspose.PDF in cloude direct access to referenced files impossible: in such case some custome code put
 into special method should be used, and delegate that refers that method should be assygned to this attribute.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### See Also

* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

