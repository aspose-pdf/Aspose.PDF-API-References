---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement sınıfı. XForm yerleşimini temsil eder. XForm sayfada 1'den fazla kez görüntüleniyorsa, bu XForm ile ilişkili tüm XFormPlacement'lar ortak grafik unsurlarına sahip olacak, ancak farklı grafik durumları olacaktır.
type: docs
weight: 11260
url: /tr/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement sınıfı

XForm yerleşimini temsil eder. XForm sayfada 1'den fazla kez görüntüleniyorsa, bu XForm ile ilişkili tüm XFormPlacement'lar ortak grafik unsurlarına sahip olacak, ancak farklı grafik durumları olacaktır.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Bu XForm içindeki grafik unsurları alır. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Grafik unsuru matrisini alır. Matris, unsur oluşturulduğunda ayarlanır. SetPosition() çağrıldığında değişir. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | XForm'un adını alır. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Unsuru temsil eden operatörlerin koleksiyonunu alır. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Unsurun bulunduğu mevcut `XFormPlacement`'ı alır. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Grafik unsurunun çıkarıldığı sayfayı alır. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Bu XFormPlacement ile ilişkili XForm'u alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Mevcut unsuru sayfaya ekler. Eklemek için birçok unsur varsa, [`AddGraphics`](../../aspose.pdf/page/addgraphics/) kullanmak daha iyidir. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) sınıfı tarafından kullanılan tüm kaynakları serbest bırakır. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Mevcut unsuru sayfadan kaldırır. Kaldırmak için birçok unsur varsa, [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) kullanmak daha iyidir. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Unsuru tek bir SVG görüntüsüne dönüştürür. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Unsuru tek bir SVG görüntü dosyasına dönüştürür. |

### Ayrıca Bakınız

* sınıf [GraphicElement](../graphicelement/)
* ad alanı [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../)