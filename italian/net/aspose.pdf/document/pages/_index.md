---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del documento. Ottiene o imposta la collezione delle pagine del documento. Nota che le pagine sono numerate a partire da 1 nella collezione
type: docs
weight: 470
url: /it/net/aspose.pdf/document/pages/
---
## Proprietà Document.Pages

Ottiene o imposta la collezione delle pagine del documento. Nota che le pagine sono numerate a partire da 1 nella collezione.

```csharp
public PageCollection Pages { get; }
```

## Esempi

L'esempio seguente dimostra come operare con le pagine del documento: come ottenere il numero di pagine e come ottenere il rettangolo della pagina iniziale del documento.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Vedi Anche

* classe [PageCollection](../../pagecollection/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)