---
title: "PdfProducer.Produce"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfProducer. Создаёт поток PDF, используя указанный формат импорта. Этот пример показывает, как создать поток PDF из потока CGM"
type: docs
weight: 10
url: /ru/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Создайте поток PDF, используя указанный формат импорта. Этот пример показывает, как создать поток Pdf из потока CGM.

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
| формат | ImportFormat | Формат импорта. |
| outputStream | Stream | Вывод PDF‑потока. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток имеет значение null |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Создайте поток PDF, используя указанный формат импорта. Этот пример показывает, как создать поток Pdf из файла CGM.

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
| формат | ImportFormat | Формат импорта. |
| outputStream | Stream | Вывод PDF‑потока. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Выходной поток имеет значение null |
| ArgumentException | Имя входного файла является пустой строкой |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Создайте файл PDF, используя указанный формат импорта. Этот пример показывает, как создать файл Pdf из потока CGM.

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
| формат | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной PDF‑файл |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной поток имеет значение null |
| ArgumentException | Имя выходного файла является пустой строкой |

### См. также

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Создайте файл PDF, используя указанный формат импорта. Этот пример показывает, как создать файл Pdf из файла CGM.

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
| формат | ImportFormat | Формат импорта. |
| outputFileName | String | Выходной PDF‑файл |

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

Создайте поток PDF, используя указанный параметр импорта. Этот пример показывает, как создать поток Pdf из файла CGM.

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
| options | ImportOptions | Опция импорта. |
| outputStream | Stream | Вывод PDF‑потока. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Выходной поток имеет значение null |
| ArgumentException | Имя входного файла является пустой строкой |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать файл Pdf из потока CGM.

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
| options | ImportOptions | Опция импорта. |
| outputFileName | String | Выходной PDF‑файл. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной поток имеет значение null |
| ArgumentException | Имя выходного файла является пустой строкой |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать файл Pdf из файла CGM.

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
| options | ImportOptions | Опция импорта. |
| outputFileName | String | Вывод PDF‑потока. |

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

Создайте файл PDF, используя указанный параметр импорта. Этот пример показывает, как создать поток Pdf из потока CGM.

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
| options | ImportOptions | Опция импорта. |
| outputStream | Stream | Вывод PDF‑потока. |

### Исключения

| исключение | условие |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Исключение выбрасывается, когда файл недействителен. |
| ArgumentNullException | Входной или выходной поток имеет значение null. |

### См. также

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


