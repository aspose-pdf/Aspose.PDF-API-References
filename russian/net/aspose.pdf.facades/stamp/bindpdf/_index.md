---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Метод Stamp. Устанавливает PDF файл и номер страницы, который будет использоваться в качестве штампа
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Устанавливает PDF файл и номер страницы, который будет использоваться в качестве штампа.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfFile | String | Путь к PDF файлу. |
| pageNumber | Int32 | Номер страницы в PDF файле |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Устанавливает PDF файл и номер страницы, который будет использоваться в качестве штампа.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | Stream | Поток, содержащий PDF документ. |
| pageNumber | Int32 | Индекс страницы документа, который будет использоваться в качестве штампа. |

## Примеры

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### См. также

* класс [Stamp](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)