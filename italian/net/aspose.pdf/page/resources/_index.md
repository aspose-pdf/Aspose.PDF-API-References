---
title: "Page.Resources"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Page. Ottiene le risorse della pagina. L'oggetto Resources contiene collezioni di immagini, moduli e font. Resources"
type: docs
weight: 240
url: /it/net/aspose.pdf/page/resources/
---
## Page.Resources property

Ottiene le risorse della pagina. L'oggetto Resources contiene collezioni di immagini, moduli e font. `Resources`

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

### Vedi anche

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


