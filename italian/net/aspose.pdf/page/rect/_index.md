---
title: "Page.Rect"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Page. Ottiene o imposta il rettangolo della pagina. Per l'operazione di lettura viene restituita la crop box della pagina se specificata, altrimenti viene restituita la media box. Per l'impostazione viene sempre impostata la media box. Si noti che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina tenendo conto della rotazione, utilizzare ActualRect"
type: docs
weight: 230
url: /it/net/aspose.pdf/page/rect/
---
## Page.Rect property

Ottiene o imposta il rettangolo della pagina. Per l'ottenimento: viene restituito il crop box della pagina se specificato, altrimenti viene restituito il media box della pagina. Per l'impostazione: il media box della pagina è sempre impostato. Si noti che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, utilizzare ActualRect.

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

### Vedi anche

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


