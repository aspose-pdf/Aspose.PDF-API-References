---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene o imposta il bleed box della pagina
type: docs
weight: 70
url: /it/net/aspose.pdf/page/bleedbox/
---
## Proprietà Page.BleedBox

Ottiene o imposta il bleed box della pagina.

```csharp
public Rectangle BleedBox { get; set; }
```

## Esempi

L'esempio dimostra come ottenere il bleed box della pagina:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### Vedi Anche

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)