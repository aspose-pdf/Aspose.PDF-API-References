---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta il rettangolo della pagina. Per ottenere viene restituito il box di ritaglio della pagina se specificato, altrimenti viene restituito il box dei media della pagina. Per impostare il box dei media della pagina è sempre impostato. Si prega di notare che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, si prega di utilizzare ActualRect.
type: docs
weight: 230
url: /it/net/aspose.pdf/page/rect/
---
## Proprietà Page.Rect

Ottiene o imposta il rettangolo della pagina. Per ottenere: viene restituito il box di ritaglio della pagina se specificato, altrimenti viene restituito il box dei media della pagina. Per impostare: il box dei media della pagina è sempre impostato. Si prega di notare che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, si prega di utilizzare ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Esempi

L'esempio dimostra come ottenere il rettangolo della pagina:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)