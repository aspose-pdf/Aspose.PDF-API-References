---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColor sınıfı. Nonstroking işlemleri için renk ayarlamak üzere sc operatörü sınıfını temsil eder.
type: docs
weight: 7630
url: /tr/net/aspose.pdf.operators/setcolor/
---
## SetColor sınıfı

Non-stroking işlemler için renk ayarlamak üzere sc operatörünü temsil eden sınıf.

```csharp
public class SetColor : BasicSetColorOperator
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Operatörü başlatır. |
| [SetColor](setcolor/#constructor_1)(double) | DeviceGray, CalGray ve Indexed renk alanları için çizim operatörleri için rengi ayarlar. |
| [SetColor](setcolor/#constructor_4)(double[]) | Renk bileşenlerini belirtmeye olanak tanıyan yapıcı. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | DeviceRGB, CalRGB ve Lab renk alanları için çizim operatörü için rengi ayarlar. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | CMYK renk alanı için non-stroking operatörü için rengi ayarlar. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Mavi bileşeni alır veya ayarlar. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Camgöbeği bileşenini alır veya ayarlar. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Renk bileşenleri dizisini alır. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Yeşil bileşeni alır veya ayarlar. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Gri rengin siyah bileşenini alır. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Sayfa operatörleri listesindeki operatör indeksini alır veya ayarlar. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Siyah bileşeni alır veya ayarlar. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Macenta bileşenini alır veya ayarlar. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Kırmızı bileşeni alır veya ayarlar. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Sarı bileşeni alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Operatör tarafından belirtilen rengi döndürür. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Rengin string temsilini döndürür. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Bu örneği verilen nesne ile karşılaştırır. |

### Ayrıca Bakınız

* sınıf [BasicSetColorOperator](../basicsetcoloroperator/)
* ad alanı [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* derleme [Aspose.PDF](../../)