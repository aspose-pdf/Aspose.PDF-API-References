---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke sınıfı. Renk çizme operatörleri için renk ayarlayan SC operatörünü temsil eden sınıf
type: docs
weight: 7680
url: /tr/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke Sınıfı

Renk çizme operatörleri için renk ayarlayan SC operatörünü temsil eden sınıf.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Operatörü başlatır. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | DeviceGray, CalGray ve Indexed renk alanları için çizme operatörleri için rengi ayarlar. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Renk bileşenlerini ayarlamaya olanak tanıyan yapıcı. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | DeviceRGB, CalRGB ve Lab renk alanı için çizme operatörü için rengi ayarlar. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | CMYK renk alanı için çizme operatörü için rengi ayarlar. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Mavi bileşeni alır veya ayarlar. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Camgöbeği bileşeni alır veya ayarlar. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Renk bileşenleri dizisini alır. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Yeşil bileşeni alır veya ayarlar. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gri rengin siyah bileşenini alır. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Sayfa operatörleri listesinde operatör indeksini alır veya ayarlar. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Siyah bileşeni alır veya ayarlar. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Macenta bileşeni alır veya ayarlar. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Kırmızı bileşeni alır veya ayarlar. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Sarı bileşeni alır veya ayarlar. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Operatör tarafından belirtilen rengi döndürür. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Operatörün metnini ve parametrelerini döndürür. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Bu örneği verilen nesne ile karşılaştırır. |

### Ayrıca Bakınız

* sınıf [BasicSetColorOperator](../basicsetcoloroperator/)
* ad alanı [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* derleme [Aspose.PDF](../../)