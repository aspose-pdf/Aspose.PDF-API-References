---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix sınıfı. Sınıf, dönüşüm matrisini temsil eder
type: docs
weight: 6920
url: /tr/net/aspose.pdf/matrix/
---
## Matris sınıfı

Sınıf, dönüşüm matrisini temsil eder.

```csharp
public sealed class Matrix
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Matrix](matrix/#constructor)() | Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Yapıcı, aşağıdaki dizi temsiline sahip bir matris kabul eder: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Yapıcı, aşağıdaki dizi temsiline sahip bir matris kabul eder: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Yapıcı, bir kopya oluşturmak için bir matris kabul eder |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Belirtilen katsayılarla dönüşüm matrisini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Dönüşüm matrisinin A üyesi. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Dönüşüm matrisinin B üyesi. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Dönüşüm matrisinin C üyesi. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Dönüşüm matrisinin D üyesi. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Matrisi dizi olarak alır. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Dönüşüm matrisinin E üyesi. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Matrisin elemanları. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Dönüşüm matrisinin F üyesi. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Verilen döndürme açısı için matris oluşturur. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Verilen döndürme için matris oluşturur. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Verilen matrise ölçekleme uygular. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Verilen döndürme açısı için matris oluşturur. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Matrisi x ve y yönünde belirtilen miktarda çevirir. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Matrisi diğer matrise ekler. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Matrisi diğer nesne ile karşılaştırır. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Çevirme matrisini alır. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Nesne için hash kodu. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Matrisi diğer matris ile çarpar. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Ters matrisi hesaplar. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Aşağıdaki formülü kullanarak matrisi x ve y ile ölçekler: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Matrisin metin temsilini döndürür. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Bu matrisi kullanarak noktayı dönüştürür. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Dikdörtgeni dönüştürür. Açı 90 * N derece değilse, sınırlayıcı dikdörtgen döndürülür. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Bu matrisi kullanarak koordinatları dönüştürür. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | x1 ve y1'i geri ölçekler ve matris dönüşümünden önce x ve y'yi aşağıdaki formülü kullanarak döndürür: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | x1 ve y1'i geri dönüştürür ve matris dönüşümünden önce x ve y'yi aşağıdaki formülü kullanarak döndürür: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Dönmeyi açıya (derece) çevirir |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)