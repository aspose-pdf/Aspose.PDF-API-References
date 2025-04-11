---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. Bir belgede dijital imzaların sağladığı kapsama seviyesini temsil eden enum
type: docs
weight: 10110
url: /tr/net/aspose.pdf.signatures/signaturescoverage/
---
## İmza Kapsamı enumerasyonu

Bir belgede dijital imzaların sağladığı kapsama seviyesini temsil eden enum.

```csharp
public enum SignaturesCoverage
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Tanımsız | `0` | Belgedeki dijital imzaların kapsam durumunun tanımsız olduğunu gösterir. Bu değer, belgede bir veya daha fazla imzanın tehlikeye girdiği veya doğrulanamadığı durumlarda kullanılır ve belgenin imza kapsamının kesin bir değerlendirmesini engeller. |
| Tamamenİmzalı | `1` | Belgenin tamamen dijital imzalarla kaplandığını gösterir. Bu değer, belgenin gerekli tüm kısımlarının imzalandığını ve hiçbir imzanın tehlikeye girmediğini belirtir. |
| Kısmenİmzalı | `2` | Belgenin kısmen imzalandığını, yani içeriğinin bir kısmının dijital imzalarla kaplandığını, ancak tamamının kaplanmadığını gösterir. Bu değer, belgenin belirli kısımlarının imzasız kaldığı veya imza kapsamından hariç tutulduğu durumlarda kullanılır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)