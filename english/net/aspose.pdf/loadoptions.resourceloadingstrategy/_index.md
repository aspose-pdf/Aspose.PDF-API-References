---
title: "LoadOptions.ResourceLoadingStrategy Delegate"
linktitle: "LoadOptions.ResourceLoadingStrategy"
articleTitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF for .NET API Reference"
description: "Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested reso..."
type: docs
weight: 1830
url: "/net/aspose.pdf/loadoptions.resourceloadingstrategy/"
product_version: "26.9.0"
---
## LoadOptions.ResourceLoadingStrategy delegate

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes)
 and supply custom method, that will get requested resources from somewhere. For example during usage 
 of Aspose.Pdf in cloud direct access to referenced files impossible, and some custome code put into special
 method should be used.
 This delegate defines signature of such custom method.

```csharp
public delegate void ResourceLoadingStrategy()
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

