---
title: "PdfExtractor.BindPdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Привязать входной PDF‑файл"
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Привязать входной PDF‑файл.

```csharp
public override void BindPdf(string inputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | String | PDF‑файл для привязки |

## Примеры

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Привязывает PDF‑документ из потока.

```csharp
public override void BindPdf(Stream inputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Поток, содержащий данные PDF‑документа |

## Примеры

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


