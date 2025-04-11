---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin enum. Çizgi birleşim stili, çizilen yolların köşelerinde kullanılacak şekli belirtmelidir.
type: docs
weight: 7450
url: /tr/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumerasyonu

Çizgi birleşim stili, çizilen yolların köşelerinde kullanılacak şekli belirtmelidir.

```csharp
public enum LineJoin
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| MiterJoin | `0` | Miter birleşimi. İki segmentin dış kenarları, bir resim çerçevesinde olduğu gibi bir açıda buluşana kadar uzatılmalıdır. Segmentler, miter limit parametresi tarafından tanımlanan çok keskin bir açıda buluşuyorsa (bkz. 8.4.3.5, "Miter Limiti"), bunun yerine bir bevel birleşimi kullanılmalıdır. |
| RoundJoin | `1` | Yuvarlak birleşim. İki segmentin buluştuğu noktada, çizgi genişliğine eşit bir çapta bir dairenin arkı çizilecektir ve bu, iki segmentin dış kenarlarını birleştirecektir. Bu dilim şeklindeki figür doldurulacak ve yuvarlak bir köşe oluşturacaktır. |
| BevelJoin | `2` | Bevel birleşimi. İki segment, uç kapaklarla (bkz. 8.4.3.3, "Çizgi Kapak Stili") bitirilecektir ve segmentlerin uçlarının ötesindeki oluşan çentik bir üçgenle doldurulacaktır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)