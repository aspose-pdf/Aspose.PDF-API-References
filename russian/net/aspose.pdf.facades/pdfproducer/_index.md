---
title: "Класс PdfProducer"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfProducer. Представляет класс для создания PDF из других форматов. Этот пример показывает, как создать файл Pdf из файла CGM."
type: docs
weight: 4730
url: /ru/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Представляет класс для создания PDF из других форматов. Этот пример показывает, как создать файл Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Файл pdf успешно создан.
}
catch (InvalidCgmFileFormatException e)
{
    //  Выполнить действие...
}
```

```csharp
public abstract class PdfProducer
```

## Методы

| Имя | Описание |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | Создайте поток PDF, используя указанный формат импорта. Этот пример показывает, как создать поток Pdf из потока CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | Создайте файл PDF, используя указанный формат импорта. Этот пример показывает, как создать файл Pdf из потока CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать поток Pdf из потока CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать файл Pdf из потока CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | Создайте поток PDF, используя указанный формат импорта. Этот пример показывает, как создать поток Pdf из файла CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | Создайте файл PDF, используя указанный формат импорта. Этот пример показывает, как создать файл Pdf из файла CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | Создайте поток PDF, используя указанный параметр импорта. Этот пример показывает, как создать поток Pdf из файла CGM. |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать файл Pdf из файла CGM. |

### См. также

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


