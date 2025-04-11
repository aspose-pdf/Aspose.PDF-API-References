---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Menentukan subtable encoding. Setiap subtable encoding memiliki kombinasi parameter yang unik yaitu PlatformID dan PlatformSpecificId. Enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) dan properti [`CMapEncodingTable`](./cmapencodingtable/) diimplementasikan untuk mempermudah pengaturan subtable encoding yang diperlukan.
type: docs
weight: 8340
url: /id/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Kelas PdfASymbolicFontEncodingStrategy.QueueItem

Menentukan subtable encoding. Setiap subtable encoding memiliki kombinasi parameter yang unik (PlatformID, PlatformSpecificId). Enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) dan properti [`CMapEncodingTable`](./cmapencodingtable/) diimplementasikan untuk mempermudah pengaturan subtable encoding yang diperlukan.

```csharp
public class QueueItem
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Konstruktor, menentukan subtable mac(1,0) secara default |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Konstruktor |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Konstruktor |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Menentukan subtable encoding melalui enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identifikasi platform untuk subtable encoding |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identifikasi encoding spesifik platform untuk subtable encoding |

### Lihat Juga

* kelas [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)