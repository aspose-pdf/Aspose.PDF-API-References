---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Page-egenskap. Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och typsnitt. Resurser
type: docs
weight: 240
url: /sv/net/aspose.pdf/page/resources/
---
## Page.Resources-egenskap

Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och typsnitt. `Resources`

```csharp
public Resources Resources { get; }
```

## Exempel

Exemplet visar hur man skannar igenom sidbilder:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Se Även

* klass [Resources](../../resources/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)