---
title: "PdfASymbolicFontEncodingStrategy.QueueItem Class"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
articleTitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PdfASymbolicFontEncodingStrategy.QueueItem class. Specifies encoding subtable. Each encoding subtable has unique combination of parameters (Platfo..."
type: docs
weight: 2370
url: "/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/"
keywords: "PdfASymbolicFontEncodingStrategy.QueueItem, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Specifies encoding subtable. Each encoding subtable has unique combination
 of parameters (PlatformID, PlatformSpecificId). Enumeration `CMapEncodingTableType`
 and property `CMapEncodingTable` were implemented to make easier 
 set of encoding subtable needed.

```csharp
public class QueueItem
```

## Constructors

| Name | Description |
| --- | --- |
| [QueueItem](./queueitem/#constructor)() | Constructor, specifies mac subtable(1,0) by default |
| [QueueItem](./queueitem/#constructor_1)(CMapEncodingTableType) | Constructor |
| [QueueItem](./queueitem/#constructor_2)(ushort, ushort) | Constructor |

## Properties

| Name | Description |
| --- | --- |
| [CMapEncodingTable](./cmapencodingtable/) { get; set; } | Specifies encoding subtable via `CMapEncodingTableType`enumeration |
| [PlatformId](./platformid/) { get; set; } | Platform identifier for encoding subtable |
| [PlatformSpecificId](./platformspecificid/) { get; set; } | Platform-specific encoding identifier for encoding subtable |

## Other Members

| Name | Description |
| --- | --- |
| enum [CMapEncodingTableType](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) | Declares set of some known encoding subtables |

### See Also

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

