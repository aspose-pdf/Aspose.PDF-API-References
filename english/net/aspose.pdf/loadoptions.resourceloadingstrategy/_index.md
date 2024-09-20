---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Sometimes its necessary to avoid usage of internal loader of external resourceslike images or CSSes and supply custom method that will get requested resources from somewhere. For example during usage of Aspose.Pdf in cloud direct access to referenced files impossible and some custome code put into special method should be used. This delegate defines signature of such custom method
type: docs
weight: 4530
url: /net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.Pdf in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceURI | String | Resource URI. |

### Return Value

ResourceLoadingResult object.

### See Also

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


