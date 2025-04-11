---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath sınıfı. Sayfadaki vektör grafik nesnesini temsil eder. Temelde vektör grafik nesneleri iki grup SubPath ile temsil edilir. Bunlardan biri bir dizi çizgi ve eğri ile temsil edilir. Diğerleri dikdörtgenler olarak sunulur ve bazen karıştırılabilir. Genellikle bir rengi olan dikdörtgen bir alan olup, çok sık olarak bu dikdörtgen sayfanın başında yer alır ve sayfanın tamamını beyaz olarak tanımlar. Böylece SubPath'ı alırsınız, ancak görsel olarak sayfadaki metni yalnızca görürsünüz.
type: docs
weight: 11220
url: /tr/net/aspose.pdf.vector/subpath/
---
## SubPath sınıfı

Sayfadaki vektör grafik nesnesini temsil eder. Temelde, vektör grafik nesneleri iki grup SubPath ile temsil edilir. Bunlardan biri bir dizi çizgi ve eğri ile temsil edilir. Diğerleri dikdörtgenler olarak sunulur ve bazen karıştırılabilir. Genellikle bir rengi olan dikdörtgen bir alan olup, çok sık olarak bu dikdörtgen sayfanın başında yer alır ve sayfanın tamamını beyaz olarak tanımlar. Böylece SubPath'ı alırsınız, ancak görsel olarak sayfadaki metni yalnızca görürsünüz.

```csharp
public sealed class SubPath : GraphicElement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Grafik öğesi matrisini alır. Matris, öğe oluşturulduğunda ayarlanır. SetPosition() çağrıldığında değişir. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Öğeyi temsil eden operatörlerin koleksiyonunu alır. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Öğenin bulunduğu mevcut [`XFormPlacement`](../xformplacement/) değerini alır. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Mevcut koordinat alanındaki konumu alır veya ayarlar. Eğer [`Parent`](../graphicelement/parent/) !:null değilse, o zaman öğenin xForm koordinat alanı vardır. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Grafik öğesinin çıkarıldığı sayfayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Mevcut öğeyi sayfaya ekler. Eklemek için birçok öğe varsa, daha iyi bir şekilde [`AddGraphics`](../../aspose.pdf/page/addgraphics/) kullanın. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) sınıfı tarafından kullanılan tüm kaynakları serbest bırakır. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Mevcut öğeyi sayfadan kaldırır. Kaldırmak için birçok öğe varsa, daha iyi bir şekilde [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/) kullanın. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Öğeyi tek bir SVG görüntüsüne dönüştürür. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Öğeyi tek bir SVG görüntü dosyasına dönüştürür. |

### Ayrıca Bakınız

* sınıf [GraphicElement](../graphicelement/)
* ad alanı [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../)