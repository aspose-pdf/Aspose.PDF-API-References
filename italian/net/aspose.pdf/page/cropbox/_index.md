---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta il riquadro di ritaglio della pagina
type: docs
weight: 100
url: /it/net/aspose.pdf/page/cropbox/
---
## Proprietà Page.CropBox

Ottiene o imposta il riquadro di ritaglio della pagina.

```csharp
public Rectangle CropBox { get; set; }
```

## Esempi

L'esempio dimostra come ottenere il riquadro di ritaglio della pagina:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)