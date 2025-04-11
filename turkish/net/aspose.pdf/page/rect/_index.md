---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın dikdörtgenini alır veya ayarlar. Almak için: belirtilmişse sayfa kırpma kutusu döndürülür, aksi takdirde sayfa medya kutusu döndürülür. Ayarlamak için: sayfa medya kutusu her zaman ayarlanır. Lütfen bu özelliğin sayfa döndürmesini dikkate almadığını unutmayın. Döndürmeyi dikkate alarak sayfa dikdörtgenini almak için lütfen ActualRect kullanın.
type: docs
weight: 230
url: /tr/net/aspose.pdf/page/rect/
---
## Page.Rect özelliği

Sayfanın dikdörtgenini alır veya ayarlar. Almak için: belirtilmişse sayfa kırpma kutusu döndürülür, aksi takdirde sayfa medya kutusu döndürülür. Ayarlamak için: sayfa medya kutusu her zaman ayarlanır. Lütfen bu özelliğin sayfa döndürmesini dikkate almadığını unutmayın. Döndürmeyi dikkate alarak sayfa dikdörtgenini almak için lütfen ActualRect kullanın.

```csharp
public Rectangle Rect { get; set; }
```

## Örnekler

Örnek, sayfa dikdörtgenini almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)