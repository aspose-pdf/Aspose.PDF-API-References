---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta la cornice artistica della pagina
type: docs
weight: 30
url: /it/net/aspose.pdf/page/artbox/
---
## Proprietà Page.ArtBox

Ottiene o imposta la cornice artistica della pagina.

```csharp
public Rectangle ArtBox { get; set; }
```

## Esempi

L'esempio dimostra come ottenere la cornice artistica della pagina:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)