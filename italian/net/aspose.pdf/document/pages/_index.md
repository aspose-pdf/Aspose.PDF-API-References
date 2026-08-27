---
title: "Document.Pages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Document property. Ottiene o imposta la collezione di pagine del documento. Nota che le pagine sono numerate a partire da 1 nella collezione"
type: docs
weight: 490
url: /it/net/aspose.pdf/document/pages/
---
## Document.Pages property

Ottiene o imposta la raccolta di pagine del documento. Nota che le pagine sono numerate a partire da 1 nella raccolta.

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

### Vedi anche

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


