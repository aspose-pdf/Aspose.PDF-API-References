---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do documento. Obtém ou define a coleção de páginas do documento. Observe que as páginas são numeradas a partir de 1 na coleção
type: docs
weight: 470
url: /pt/net/aspose.pdf/document/pages/
---
## Propriedade Document.Pages

Obtém ou define a coleção de páginas do documento. Observe que as páginas são numeradas a partir de 1 na coleção.

```csharp
public PageCollection Pages { get; }
```

## Exemplos

O exemplo abaixo demonstra como operar com as páginas do documento: Como obter o número de páginas e como obter o retângulo da página inicial do documento.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Veja Também

* classe [PageCollection](../../pagecollection/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)