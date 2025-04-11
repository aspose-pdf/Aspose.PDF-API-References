---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions sınıfı. Yan yana çıktı ile belgeleri karşılaştırmak için bir seçenek sınıfını temsil eder.
type: docs
weight: 3290
url: /tr/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions sınıfı

Yan yana çıktı ile belgeleri karşılaştırmak için bir seçenek sınıfını temsil eder.

```csharp
public class SideBySideComparisonOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Ek değişiklik işaretlerinin görüntülenip görüntülenmeyeceğini belirleyen özelliği alır ve ayarlar. Ayarlandığında, mevcut sayfada olmayan ancak başka bir sayfada bulunan değişiklik işaretlerini gösterir. Değişiklik kelimeler arasında yer alıyorsa, işaret boşluk karakterine göre tam olarak konumlandırılmayabilir. Varsayılan değer `false`'dır. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yöntemindeki ilk sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) ve [`ExcludeAreas2`](./excludeareas2/) seçenekleri ile birlikte ayarlanamaz. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Karşılaştırma alanını alır ve ayarlar. Karşılaştırma yöntemindeki ikinci sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) ve [`ExcludeAreas2`](./excludeareas2/) seçenekleri ile birlikte ayarlanamaz. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Bir karşılaştırma modunu alır ve ayarlar. Varsayılan değer !:SideBySideComparison.ComparisonMode.IgnoreSpaces'tır. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Hariç tutulan alanları alır ve ayarlar. Karşılaştırma yöntemindeki ilk sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/) ile birlikte ayarlanabilir. Bu seçenek [`ComparisonArea1`](./comparisonarea1/) seçeneği ile birlikte ayarlanamaz. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Hariç tutulan alanları alır ve ayarlar. Karşılaştırma yöntemindeki ikinci sayfa veya belge için kullanılır. Bu seçenek [`ExcludeTables`](./excludetables/) ile birlikte ayarlanabilir. Bu seçenek [`ComparisonArea2`](./comparisonarea2/) seçeneği ile birlikte ayarlanamaz. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Karşılaştırmadan tabloların hariç tutulup tutulmayacağını belirleyen seçeneği alır ve ayarlar. Bu seçenek [`ComparisonArea1`](./comparisonarea1/) ve [`ComparisonArea2`](./comparisonarea2/) ile birlikte ayarlanamaz. Varsayılan değer `false`'dır. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)