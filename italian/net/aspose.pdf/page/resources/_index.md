---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene le risorse della pagina. L'oggetto Risorse contiene collezioni di immagini, moduli e caratteri. Risorse
type: docs
weight: 240
url: /it/net/aspose.pdf/page/resources/
---
## Proprietà Page.Resources

Ottiene le risorse della pagina. L'oggetto Risorse contiene collezioni di immagini, moduli e caratteri. `Resources`

```csharp
public Resources Resources { get; }
```

## Esempi

L'esempio dimostra la scansione delle immagini della pagina:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Vedi Anche

* classe [Resources](../../resources/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)