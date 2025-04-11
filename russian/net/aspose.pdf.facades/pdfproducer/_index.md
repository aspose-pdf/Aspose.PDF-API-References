---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfProducer. Представляет класс для создания PDF из других форматов. Этот пример показывает, как создать файл Pdf из файла CGM
type: docs
weight: 4610
url: /ru/net/aspose.pdf.facades/pdfproducer/
---
## Класс PdfProducer

Представляет класс для создания PDF из других форматов. Этот пример показывает, как создать файл Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Success produced pdf file.
}
catch (InvalidCgmFileFormatException e)
{
    //  Do something...
}
```

```csharp
public abstract class PdfProducer
```

## Методы

| Название | Описание |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Создает PDF поток с использованием указанного формата импорта. Этот пример показывает, как создать Pdf поток из CGM потока. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Создает PDF файл с использованием указанного формата импорта. Этот пример показывает, как создать Pdf файл из CGM потока. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Создает PDF файл с использованием указанного варианта импорта. Этот пример показывает, как создать Pdf поток из CGM потока. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Создает PDF файл с использованием указанного варианта импорта. Этот пример показывает, как создать Pdf файл из CGM потока. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Создает PDF поток с использованием указанного формата импорта. Этот пример показывает, как создать Pdf поток из CGM файла. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Создает PDF файл с использованием указанного формата импорта. Этот пример показывает, как создать Pdf файл из CGM файла. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Создает PDF поток с использованием указанного варианта импорта. Этот пример показывает, как создать Pdf поток из CGM файла. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Создает PDF файл с использованием указанного варианта импорта. Этот пример показывает, как создать Pdf файл из CGM файла. |

### См. также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)