---
title: "PdfProducer.Produce"
linktitle: "Produce"
articleTitle: "Produce"
second_title: "Aspose.PDF for .NET"
description: "Produce the PDF stream using specified import format. This sample shows how to produce Pdf stream from CGM stream. string inputFile = \"myImage.cgm\"; string o..."
type: docs
weight: 20
url: "/net/aspose.pdf.facades/pdfproducer/produce/"
product_version: "26.9.0"
---
## Produce(Stream, [ImportFormat](../../../aspose.pdf/importformat/), Stream) {#produce}

Produce the PDF stream using specified import format.
 This sample shows how to produce Pdf stream from CGM stream.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream inputStream = File.OpenRead(inputFile))
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
 }

```csharp
public void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input stream. |
| format | ImportFormat | Import format. |
| outputStream | Stream | Output PDF stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Input or output stream is null |

## Examples

This sample shows how to produce Pdf stream from CGM stream.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream inputStream = File.OpenRead(inputFile))
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
 }
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, [ImportFormat](../../../aspose.pdf/importformat/), Stream) {#produce_1}

Produce the PDF stream using specified import format.
 This sample shows how to produce Pdf stream from CGM file.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
 }

```csharp
public void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | string | Input file name. |
| format | ImportFormat | Import format. |
| outputStream | Stream | Output PDF stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Output stream is null |
| ArgumentException | Input file name is an empty string |

## Examples

This sample shows how to produce Pdf stream from CGM file.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
 }
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, [ImportFormat](../../../aspose.pdf/importformat/), string) {#produce_2}

Produce the PDF file using specified import format.
 This sample shows how to produce Pdf file from CGM stream.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream inputStream = File.OpenRead(inputFile))
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
 }

```csharp
public void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input stream. |
| format | ImportFormat | Import format. |
| outputFileName | string | Output PDF file |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Input stream is null |
| ArgumentException | Output file name is an empty string |

## Examples

This sample shows how to produce Pdf file from CGM stream.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 using (FileStream inputStream = File.OpenRead(inputFile))
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
 }
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, [ImportFormat](../../../aspose.pdf/importformat/), string) {#produce_3}

Produce the PDF file using specified import format.
 This sample shows how to produce Pdf file from CGM file.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);

```csharp
public void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | string | Input file name. |
| format | ImportFormat | Import format. |
| outputFileName | string | Output PDF file |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentException | Input or output file name is an empty string |

## Examples

This sample shows how to produce Pdf file from CGM file.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, [ImportOptions](../../../aspose.pdf/importoptions/), Stream) {#produce_4}

Produce the PDF stream using specified import option.
 This sample shows how to produce Pdf stream from CGM file.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputFile, importOptions, outputStream);
 }

```csharp
public void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | string | Input file name. |
| options | ImportOptions | Import option. |
| outputStream | Stream | Output PDF stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Output stream is null |
| ArgumentException | Input file name is an empty string |

## Examples

This sample shows how to produce Pdf stream from CGM file.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputFile, importOptions, outputStream);
 }
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, [ImportOptions](../../../aspose.pdf/importoptions/), string) {#produce_5}

Produce the PDF file using specified import option.
 This sample shows how to produce Pdf file from CGM stream.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileStream inputStream = File.OpenRead(inputFile))
 {
 PdfProducer.Produce(inputStream, importOptions, outputFile);
 }

```csharp
public void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input stream. |
| options | ImportOptions | Import option. |
| outputFileName | string | Output PDF file. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Input stream is null |
| ArgumentException | Output file name is an empty string |

## Examples

This sample shows how to produce Pdf file from CGM stream.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileStream inputStream = File.OpenRead(inputFile))
 {
 PdfProducer.Produce(inputStream, importOptions, outputFile);
 }
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, [ImportOptions](../../../aspose.pdf/importoptions/), string) {#produce_6}

Produce the PDF file using specified import option.
 This sample shows how to produce Pdf file from CGM file.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 PdfProducer.Produce(inputStream, importOptions, outputStream);

```csharp
public void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | string | Input file name. |
| options | ImportOptions | Import option. |
| outputFileName | string | Output PDF stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentException | Input or output file name is an empty string |

## Examples

This sample shows how to produce Pdf file from CGM file.

```csharp
string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 PdfProducer.Produce(inputStream, importOptions, outputStream);
```

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, [ImportOptions](../../../aspose.pdf/importoptions/), Stream) {#produce_7}

Produce the PDF file using specified import option.
 This sample shows how to produce Pdf stream from CGM stream.
 
 string inputFile = "myImage.cgm";
 string outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileStream inputStream = File.OpenRead(inputFile))
 using (FileStream outputStream = File.Create(outputFile))
 {
 PdfProducer.Produce(inputStream, importOptions, outputStream);
 }

```csharp
public void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input stream. |
| options | ImportOptions | Import option. |
| outputStream | Stream | Output PDF stream. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | The exception is thrown when a file is invalid. |
| ArgumentNullException | Input or output stream is null. |

## Examples

This sample shows how to produce Pdf stream from CGM stream.

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

### See Also

* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

