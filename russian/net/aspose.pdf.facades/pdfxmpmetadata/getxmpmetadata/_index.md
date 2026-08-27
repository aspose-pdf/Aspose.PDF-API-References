---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfXmpMetadata. Получает XmpMetadata входного PDF в формате XML"
type: docs
weight: 190
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Получить XmpMetadata входного pdf в формате xml.

```csharp
public byte[] GetXmpMetadata()
```

### Возвращаемое значение

Байты XmpMetadata.

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Получить часть XmpMetadata входного pdf согласно имени метаданных.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Имя метаданных. |

### Возвращаемое значение

Байты метаданных.

## Примеры

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### См. также

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


