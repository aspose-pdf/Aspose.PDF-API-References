---
title: "PdfXmpMetadata.Item"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfXmpMetadata. Получает или задает значение по ключу"
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Получает или задает значение по ключу.

```csharp
public XmpValue this[string key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| ключ | Имя ключа для получения/задания. |

### Возвращаемое значение

Объект по ключу

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Получает значение XMP‑метаданных по ключу.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| ключ | Ключ значения. |

### Возвращаемое значение

Значение из XMP‑метаданных.

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### См. также

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


