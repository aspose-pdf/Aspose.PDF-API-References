---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem sınıfı. Kodlama alt tablosunu belirtir. Her kodlama alt tablosu, PlatformID ve PlatformSpecificId parametrelerinin benzersiz bir kombinasyonuna sahiptir. Kodlama alt tablosunun gerekli setini kolaylaştırmak için CMapEncodingTableType sayımı ve CMapEncodingTable özelliği uygulanmıştır.
type: docs
weight: 8340
url: /tr/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem sınıfı

Kodlama alt tablosunu belirtir. Her kodlama alt tablosu, (PlatformID, PlatformSpecificId) parametrelerinin benzersiz bir kombinasyonuna sahiptir. Kodlama alt tablosunun gerekli setini kolaylaştırmak için [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) sayımı ve [`CMapEncodingTable`](./cmapencodingtable/) özelliği uygulanmıştır.

```csharp
public class QueueItem
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Yapıcı, varsayılan olarak mac alt tablosunu (1,0) belirtir |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Yapıcı |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Yapıcı |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) sayımı aracılığıyla kodlama alt tablosunu belirtir |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Kodlama alt tablosu için platform tanımlayıcısı |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı |

### Ayrıca Bakınız

* sınıf [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)