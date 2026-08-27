---
title: "Page.Resources"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page‑egenskap. Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och teckensnitt. Resources"
type: docs
weight: 240
url: /sv/net/aspose.pdf/page/resources/
---
## Page.Resources property

Hämtar sidresurser. Resursobjektet innehåller samlingar av bilder, formulär och teckensnitt. `Resources`

```csharp
public Resources Resources { get; }
```

## Exempel

Exempel visar skanning genom sidbilder:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Se även

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


