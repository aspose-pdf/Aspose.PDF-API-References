---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Belge özelliği. Belge sayfalarının koleksiyonunu alır veya ayarlar. Sayfaların koleksiyonda 1'den başladığını unutmayın.
type: docs
weight: 470
url: /tr/net/aspose.pdf/document/pages/
---
## Document.Pages özelliği

Belge sayfalarının koleksiyonunu alır veya ayarlar. Sayfaların koleksiyonda 1'den başladığını unutmayın.

```csharp
public PageCollection Pages { get; }
```

## Örnekler

Aşağıdaki örnek, belge sayfalarıyla nasıl çalışılacağını gösterir: Sayfa sayısını nasıl alacağınız ve belgenin başlangıç sayfasının dikdörtgenini nasıl alacağınız.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Ayrıca Bakınız

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)