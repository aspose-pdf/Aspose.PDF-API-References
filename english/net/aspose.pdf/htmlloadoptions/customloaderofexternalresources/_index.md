---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: HtmlLoadOptions field. Sometimes its necessary to avoid usage of internal loader of external resourceslike images or CSSes and supply custom method that will get requested resources from somewhere. For example during usage of Aspose.PDF in cloude direct access to referenced files impossible in such case some custome code put into special method should be used and delegate that refers that method should be assygned to this attribute
type: docs
weight: 100
url: /net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method that will get requested resources from somewhere. For example, during usage of Aspose.PDF in cloude direct access to referenced files impossible: in such case some custome code put into special method should be used, and delegate that refers that method should be assygned to this attribute.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### See Also

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


