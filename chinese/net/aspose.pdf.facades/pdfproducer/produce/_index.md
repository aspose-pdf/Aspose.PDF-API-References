---
title: Produce
second_title: Aspose.PDF for .NET API 参考
description: 使用指定的导入格式生成 PDF 流 此示例显示如何从 CGM 流生成 Pdf 流
type: docs
weight: 10
url: /zh/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

使用指定的导入格式生成 PDF 流。 此示例显示如何从 CGM 流生成 Pdf 流。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| format | ImportFormat | 导入格式。 |
| outputStream | Stream | 输出 PDF 流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输入或输出流为空 |

### 也可以看看

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

使用指定的导入格式生成 PDF 流。 此示例显示如何从 CGM 文件生成 Pdf 流。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | String | 输入文件名。 |
| format | ImportFormat | 导入格式。 |
| outputStream | Stream | 输出 PDF 流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输出流为空 |
| ArgumentException | 输入文件名是一个空字符串 |

### 也可以看看

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

使用指定的导入格式生成 PDF 文件。 此示例显示如何从 CGM 流生成 Pdf 文件。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| format | ImportFormat | 导入格式。 |
| outputFileName | String | 输出 PDF 文件 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输入流为空 |
| ArgumentException | 输出文件名是一个空字符串 |

### 也可以看看

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

使用指定的导入格式生成 PDF 文件。 此示例显示如何从 CGM 文件生成 Pdf 文件。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | String | 输入文件名。 |
| format | ImportFormat | 导入格式。 |
| outputFileName | String | 输出 PDF 文件 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentException | 输入或输出文件名是空字符串 |

### 也可以看看

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

使用指定的导入选项生成 PDF 流。 此示例显示如何从 CGM 文件生成 Pdf 流。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | String | 输入文件名。 |
| options | ImportOptions | 导入选项。 |
| outputStream | Stream | 输出 PDF 流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输出流为空 |
| ArgumentException | 输入文件名是一个空字符串 |

### 也可以看看

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

使用指定的导入选项生成 PDF 文件。 此示例显示如何从 CGM 流生成 Pdf 文件。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| options | ImportOptions | 导入选项。 |
| outputFileName | String | 输出 PDF 文件。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输入流为空 |
| ArgumentException | 输出文件名是一个空字符串 |

### 也可以看看

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

使用指定的导入选项生成 PDF 文件。 此示例显示如何从 CGM 文件生成 Pdf 文件。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | String | 输入文件名。 |
| options | ImportOptions | 导入选项。 |
| outputFileName | String | 输出 PDF 流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentException | 输入或输出文件名是空字符串 |

### 也可以看看

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

使用指定的导入选项生成 PDF 文件。 此示例显示如何从 CGM 流生成 Pdf 流。

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

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| options | ImportOptions | 导入选项。 |
| outputStream | Stream | 输出 PDF 流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | 当文件无效时抛出异常。 |
| ArgumentNullException | 输入或输出流为空。 |

### 也可以看看

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* 命名空间 [Aspose.Pdf.Facades](../../pdfproducer)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
