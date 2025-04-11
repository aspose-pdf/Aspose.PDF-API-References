---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonOptions sınıfı. Bir PDF belgesi karşılaştırma seçenekleri sınıfını temsil eder
type: docs
weight: 3150
url: /tr/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions sınıfı

Bir PDF belgesi karşılaştırma seçenekleri sınıfını temsil eder.

```csharp
public class ComparisonOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Düzenleme işlemleri sırasını alır ve ayarlar. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Hariç tutulan alanları alır ve ayarlar. Karşılaştırma yönteminde birinci sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/) ile birlikte ayarlanabilir. Bu seçenek [`ExtractionArea`](./extractionarea/) seçeneği ile birlikte ayarlanamaz. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Hariç tutulan alanları alır ve ayarlar. Karşılaştırma yönteminde ikinci sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/) ile birlikte ayarlanabilir. Bu seçenek [`ExtractionArea`](./extractionarea/) seçeneği ile birlikte ayarlanamaz. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Karşılaştırmadan tabloların hariç tutulup tutulmayacağını belirleyen seçeneği alır ve ayarlar. Bu seçenek [`ExtractionArea`](./extractionarea/) seçeneği ile birlikte ayarlanamaz. Varsayılan değer `false`'dır. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Sayfaların metninin karşılaştırılacağı dikdörtgen alanı alır ve ayarlar. Bu seçenek [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) ve [`ExcludeAreas2`](./excludeareas2/) seçenekleri ile birlikte ayarlanamaz. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* derleme [Aspose.PDF](../../)