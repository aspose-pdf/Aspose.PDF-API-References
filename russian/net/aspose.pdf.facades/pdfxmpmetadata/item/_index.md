---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfXmpMetadata. Получает или устанавливает значение по ключу
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## Индексатор PdfXmpMetadata (1 из 2)

Получает или устанавливает значение по ключу.

```csharp
public XmpValue this[string key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| key | Имя ключа для получения/установки. |

### Возвращаемое значение

Объект по ключу

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### См. также

* класс [XmpValue](../../../aspose.pdf/xmpvalue/)
* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## Индексатор PdfXmpMetadata (2 из 2)

Получает значение XMP метаданных по ключу.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| key | Ключ значения. |

### Возвращаемое значение

Значение из XMP метаданных.

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### См. также

* класс [XmpValue](../../../aspose.pdf/xmpvalue/)
* перечисление [DefaultMetadataProperties](../../defaultmetadataproperties/)
* класс [PdfXmpMetadata](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)