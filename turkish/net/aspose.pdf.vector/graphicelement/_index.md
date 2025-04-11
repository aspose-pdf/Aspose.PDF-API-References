---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.GraphicElement sınıfı. Sayfadaki grafik nesnesi için temel sınıfı temsil eder
type: docs
weight: 11180
url: /tr/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement sınıfı

Sayfadaki grafik nesnesi için temel sınıfı temsil eder.

```csharp
public abstract class GraphicElement : IDisposable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Grafik öğesi matrisini alır. Matris, öğe oluşturulduğunda ayarlanır. SetPosition() çağrıldığında değişir. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Öğeyi temsil eden operatörlerin koleksiyonunu alır. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Öğenin bulunduğu mevcut [`XFormPlacement`](../xformplacement/) değerini alır. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mevcut koordinat alanındaki konumu alır veya ayarlar. Eğer [`Parent`](./parent/) !:null değilse, o zaman öğenin xForm koordinat alanı vardır. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | `GraphicElement`'in sınırlayıcı dikdörtgenini alır. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Grafik öğesinin çıkarıldığı sayfayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Mevcut öğeyi sayfaya ekler. Eklemek için birçok öğe varsa, [`AddGraphics`](../../aspose.pdf/page/addgraphics/) kullanmak daha iyidir. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | `GraphicElement` sınıfı tarafından kullanılan tüm kaynakları serbest bırakır. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Mevcut öğeyi sayfadan kaldırır. Kaldırmak için birçok öğe varsa, [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) kullanmak daha iyidir. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Öğeyi tek bir SVG görüntüsüne dönüştürür. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Öğeyi tek bir SVG görüntü dosyasına dönüştürür. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)