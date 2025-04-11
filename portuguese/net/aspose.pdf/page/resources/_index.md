---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da página. Obtém recursos da página. O objeto Resources contém coleções de imagens, formulários e fontes. Recursos
type: docs
weight: 240
url: /pt/net/aspose.pdf/page/resources/
---
## Propriedade Page.Resources

Obtém recursos da página. O objeto Resources contém coleções de imagens, formulários e fontes. `Resources`

```csharp
public Resources Resources { get; }
```

## Exemplos

O exemplo demonstra a varredura através das imagens da página:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Veja Também

* classe [Resources](../../resources/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)