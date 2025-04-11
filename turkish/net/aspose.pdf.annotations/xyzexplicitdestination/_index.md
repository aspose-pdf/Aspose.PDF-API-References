---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XYZExplicitDestination sınıfı. Sayfayı, sol üst köşesi pencerenin sol üst köşesine yerleştirilmiş (sol, üst) koordinatları ile ve sayfanın içeriğini zoom faktörü ile büyütülmüş olarak gösteren açık bir hedefi temsil eder. Sol, üst veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. 0 zoom değeri, null değeri ile aynı anlama gelir.
type: docs
weight: 2730
url: /tr/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination sınıfı

Sayfayı, sol üst köşesi pencerenin sol üst köşesine yerleştirilmiş (sol, üst) koordinatları ile ve sayfanın içeriğini zoom faktörü ile büyütülmüş olarak gösteren açık bir hedefi temsil eder. Sol, üst veya zoom parametrelerinden herhangi biri için null değeri, o parametrenin mevcut değerinin değişmeden korunacağını belirtir. 0 zoom değeri, null değeri ile aynı anlama gelir.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Uzak açık hedef oluşturur. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Yerel açık hedef oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Pencerenin sol üst köşesinin sol yatay koordinatını alır. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Hedef sayfa nesnesini alır. |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Hedef sayfa numarasını alır. |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Pencerenin sol üst köşesinin üst dikey koordinatını alır. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Zoom faktörünü alır. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Gerekirse sayfa döndürmesini dikkate alarak belirtilen sayfa konumuna hedef oluşturur. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Belirtilen sayfaya hedef oluşturur. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Belirtilen sayfanın sol üst köşesine hedef oluşturur. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Nesne durumunu string değerine dönüştürür. Örnek: "1 XYZ 100 200 3". |

## Örnekler

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Ayrıca Bakınız

* sınıf [ExplicitDestination](../explicitdestination/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)