---
title: Produce
second_title: Aspose.PDF для справочника API .NET
description: Создать поток PDF используя указанный формат импорта.  В этом примере показано как создать поток Pdf из потока CGM.
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из потока CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| format | ImportFormat | Формат импорта. |
| outputStream | Stream | Выходной PDF-поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен нулю |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Создать поток PDF, используя указанный формат импорта.  В этом примере показано, как создать поток Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| format | ImportFormat | Формат импорта. |
| outputStream | Stream | Выходной PDF-поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен нулю |
| ArgumentException | Имя входного файла — пустая строка |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из потока CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| format | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной PDF-файл |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Входной поток равен нулю |
| ArgumentException | Имя выходного файла — пустая строка |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Создать PDF-файл, используя указанный формат импорта.  В этом примере показано, как создать файл Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| format | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной PDF-файл |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла — пустая строка |

### Смотрите также

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Создать поток PDF, используя указанный параметр импорта.  В этом примере показано, как создать поток Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, importOptions, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| options | ImportOptions | Вариант импорта. |
| outputStream | Stream | Выходной PDF-поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен нулю |
| ArgumentException | Имя входного файла — пустая строка |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из потока CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputFile);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| options | ImportOptions | Вариант импорта. |
| outputFileName | String | Выходной файл PDF. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Входной поток равен нулю |
| ArgumentException | Имя выходного файла — пустая строка |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать файл Pdf из файла CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | String | Введите имя файла. |
| options | ImportOptions | Вариант импорта. |
| outputFileName | String | Выходной PDF-поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла — пустая строка |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Создайте файл PDF, используя указанный параметр импорта.  В этом примере показано, как создать поток Pdf из потока CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | Stream | Входной поток. |
| options | ImportOptions | Вариант импорта. |
| outputStream | Stream | Выходной PDF-поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Исключение выдается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен нулю. |

### Смотрите также

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* пространство имен [Aspose.Pdf.Facades](../../pdfproducer)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
