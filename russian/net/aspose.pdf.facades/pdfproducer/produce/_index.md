---
title: Produce
second_title: Aspose.PDF для справочника API .NET
description: Создать поток PDF используя указанный формат импорта.  В этом примере показано как создать поток Pdf из потока CGM. ltcodegt string inputFile  myImage.cgm string outputFile  myPdf.pdf использование FileStream inputStream  File.OpenReadinputFile использование FileStream outputStream  File.CreateoutputFile  PdfProducer.ProduceinputStream ImportFormat.Cgm outputStream  lt/codegt
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream); } &lt;/code&gt;

```csharp
public static void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| format | ImportFormat | Формат импорта. |
| outputStream | Stream | Вывод потока PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен нулю |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; using (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream); } &lt;/code&gt;

```csharp
public static void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| format | ImportFormat | Формат импорта. |
| outputStream | Stream | Вывод потока PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен нулю |
| ArgumentException | Входной файл имя - пустая строка |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream); } &lt;/code&gt;

```csharp
public static void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| format | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной файл PDF |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Входной поток равен null |
| ArgumentException | Выходной файл имя - пустая строка |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile); &lt;/code&gt;

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| format | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной файл PDF |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла является пустой строкой |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Создать поток PDF, используя указанную опцию импорта.  В этом примере показано, как создать поток Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputFile, importOptions, outputStream); } &lt;/code&gt;

```csharp
public static void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| options | ImportOptions | Параметр импорта. |
| outputStream | Stream | Вывод потока PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен нулю |
| ArgumentException | Входной файл имя - пустая строка |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); использование (FileStream inputStream = File.OpenRead(inputFile)) { PdfProducer.Produce(inputStream, importOptions, outputFile); } &lt;/code&gt;

```csharp
public static void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| options | ImportOptions | Параметр импорта. |
| outputFileName | String | Выходной файл PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Входной поток равен null |
| ArgumentException | Выходной файл имя - пустая строка |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из файла CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.Produce(inputStream, importOptions, outputStream); &lt;/code&gt;

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| options | ImportOptions | Параметр импорта. |
| outputFileName | String | Выходной поток PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла является пустой строкой |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать поток Pdf из потока CGM. &lt;code&gt; string inputFile = "myImage.cgm"; string outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); использование (FileStream inputStream = File.OpenRead(inputFile)) использование (FileStream outputStream = File.Create(outputFile)) { PdfProducer.Produce(inputStream, importOptions, outputStream); } &lt;/code&gt;

```csharp
public static void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| options | ImportOptions | Параметр импорта. |
| outputStream | Stream | Вывод потока PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение возникает, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен нулю. |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
