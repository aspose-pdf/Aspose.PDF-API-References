---
title: PdfProducer
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для создания PDF из других форматов.  В этом примере показано как создать файл Pdf из файла CGM. ltcodegt string inputFile  myImage.cgm string outputFile  myPdf.pdf try  PdfProducer.ProduceinputFile ImportFormat.Cgm outputFile // Успешно создан файл PDF.  catch InvalidCgmFileFormatException e  // Делаем что-то...  lt/codegt
type: docs
weight: 2620
url: /ru/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

Представляет класс для создания PDF из других форматов.  В этом примере показано, как создать файл Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; try { PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile); // Успешно создан файл PDF. } catch (InvalidCgmFileFormatException e) { // Делаем что-то... } &lt;/code&gt;

```csharp
public abstract class PdfProducer
```

## Методы

| Имя | Описание |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce)(Stream, ImportFormat, Stream) | Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_1)(Stream, ImportFormat, string) | Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_2)(Stream, ImportOptions, Stream) | Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать поток Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, importOptions, outputStream); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_3)(Stream, ImportOptions, string) | Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); использование (FileStream inputStream = File.OpenRead(inputFile)) { PdfProducer.Produce(inputStream, importOptions, outputFile); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_4)(string, ImportFormat, Stream) | Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; using (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_5)(string, ImportFormat, string) | Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile); &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_6)(string, ImportOptions, Stream) | Создать поток PDF, используя указанную опцию импорта.  В этом примере показано, как создать поток Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputFile, importOptions, outputStream); } &lt;/code&gt; |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce#produce_7)(string, ImportOptions, string) | Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.Produce(inputStream, importOptions, outputStream); &lt;/code&gt; |

### Смотрите также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
