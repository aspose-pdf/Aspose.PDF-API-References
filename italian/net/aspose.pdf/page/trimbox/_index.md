---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta il trim box della pagina
type: docs
weight: 290
url: /it/net/aspose.pdf/page/trimbox/
---
## Proprietà Page.TrimBox

Ottiene o imposta il trim box della pagina.

```csharp
public Rectangle TrimBox { get; set; }
```

## Esempi

L'esempio dimostra come ottenere il trim box della pagina:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)