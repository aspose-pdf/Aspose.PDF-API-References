---
title: Resources
second_title: Aspose.PDF for .NET API Reference
description: Gets page resources. Resources object contains collections of images forms and fonts. Resourcesaspose.pdf/page/resources
type: docs
weight: 240
url: /net/aspose.pdf/page/resources/
---
## Page.Resources property

Gets page resources. Resources object contains collections of images, forms and fonts. `Resources`

```csharp
public Resources Resources { get; }
```

### Examples

Example demonstrates scan through page images:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### See Also

* class [Resources](../../resources)
* class [Page](../../page)
* namespace [Aspose.Pdf](../../page)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->