---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta la media box della pagina
type: docs
weight: 180
url: /it/net/aspose.pdf/page/mediabox/
---
## Proprietà Page.MediaBox

Ottiene o imposta la media box della pagina.

```csharp
public Rectangle MediaBox { get; set; }
```

## Esempi

L'esempio dimostra come ottenere la media box della pagina:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)