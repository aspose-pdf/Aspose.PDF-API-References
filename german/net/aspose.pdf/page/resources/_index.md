---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Seitenattribut. Ruft Seitenressourcen ab. Das Ressourcenobjekt enthält Sammlungen von Bildern, Formularen und Schriftarten. Ressourcen
type: docs
weight: 240
url: /de/net/aspose.pdf/page/resources/
---
## Page.Resources-Eigenschaft

Ruft Seitenressourcen ab. Das Ressourcenobjekt enthält Sammlungen von Bildern, Formularen und Schriftarten. `Resources`

```csharp
public Resources Resources { get; }
```

## Beispiele

Das Beispiel demonstriert das Durchsuchen von Seitenbildern:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Siehe auch

* Klasse [Resources](../../resources/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)