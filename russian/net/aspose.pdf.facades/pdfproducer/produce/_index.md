---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfProducer. Создайте PDF поток, используя указанный формат импорта. Этот пример показывает, как создать Pdf поток из CGM потока
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Создайте PDF поток, используя указанный формат импорта. Этот пример показывает, как создать Pdf поток из CGM потока.

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
| outputStream | Stream | Выходной PDF поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен null |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Создайте PDF поток, используя указанный формат импорта. Этот пример показывает, как создать Pdf поток из CGM файла.

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
| inputFileName | String | Имя входного файла. |
| format | ImportFormat | Формат импорта. |
| outputStream | Stream | Выходной PDF поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен null |
| ArgumentException | Имя входного файла является пустой строкой |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Создайте PDF файл, используя указанный формат импорта. Этот пример показывает, как создать Pdf файл из CGM потока.

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
| outputFileName | String | Выходной PDF файл |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной поток равен null |
| ArgumentException | Имя выходного файла является пустой строкой |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Создайте PDF файл, используя указанный формат импорта. Этот пример показывает, как создать Pdf файл из CGM файла.

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
| inputFileName | String | Имя входного файла. |
| format | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной PDF файл |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла является пустой строкой |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Создайте PDF поток, используя указанный вариант импорта. Этот пример показывает, как создать Pdf поток из CGM файла.

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
| inputFileName | String | Имя входного файла. |
| options | ImportOptions | Вариант импорта. |
| outputStream | Stream | Выходной PDF поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Выходной поток равен null |
| ArgumentException | Имя входного файла является пустой строкой |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Создайте PDF файл, используя указанный вариант импорта. Этот пример показывает, как создать Pdf файл из CGM потока.

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
| outputFileName | String | Выходной PDF файл. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной поток равен null |
| ArgumentException | Имя выходного файла является пустой строкой |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Создайте PDF файл, используя указанный вариант импорта. Этот пример показывает, как создать Pdf файл из CGM файла.

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
| inputFileName | String | Имя входного файла. |
| options | ImportOptions | Вариант импорта. |
| outputFileName | String | Выходной PDF поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentException | Имя входного или выходного файла является пустой строкой |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Создайте PDF файл, используя указанный вариант импорта. Этот пример показывает, как создать Pdf поток из CGM потока.

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
| outputStream | Stream | Выходной PDF поток. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток равен null. |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)