---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da página. Obtém ou define a caixa de corte da página
type: docs
weight: 100
url: /pt/net/aspose.pdf/page/cropbox/
---
## Propriedade Page.CropBox

Obtém ou define a caixa de corte da página.

```csharp
public Rectangle CropBox { get; set; }
```

## Exemplos

O exemplo demonstra como obter a caixa de corte da página:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Veja Também

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)