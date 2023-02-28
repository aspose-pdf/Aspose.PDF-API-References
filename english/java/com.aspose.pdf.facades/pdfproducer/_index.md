---
title: PdfProducer
second_title: Aspose.PDF for Java API Reference
description: Represents a class to produce PDF from other formats.
type: docs
weight: 46
url: /java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object
```
public abstract class PdfProducer
```

Represents a class to produce PDF from other formats.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 try
 {
     PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
     // Success produced pdf file.
 }
 catch (Exception e)
 {
     //  Do something...
 }
```
## Methods

| Method | Description |
| --- | --- |
| [produce(InputStream inputStream, int format, OutputStream outputStream)](#produce-java.io.InputStream-int-java.io.OutputStream-) | Produce the PDF stream using specified import format. |
| [produce(String inputFileName, int format, OutputStream outputStream)](#produce-java.lang.String-int-java.io.OutputStream-) |  |
| [produce(InputStream inputStream, int format, String outputFileName)](#produce-java.io.InputStream-int-java.lang.String-) | Produce the PDF file using specified import format. |
| [produce(String inputFileName, int format, String outputFileName)](#produce-java.lang.String-int-java.lang.String-) | Produce the PDF file using specified import format. |
| [produce(String inputFileName, ImportOptions options, OutputStream outputStream)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce(InputStream inputStream, ImportOptions options, String outputFileName)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce(String inputFileName, ImportOptions options, String outputFileName)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | Produce the PDF file using specified import option. |
| [produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | Produce the PDF file using specified import option. |
| [produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |
| [getProducer(ImportOptions options)](#getProducer-com.aspose.pdf.ImportOptions-) | Get the producer for specified import option. |
| [getProducer(int format)](#getProducer-int-) | Get the producer for specified import format. |
| [getImportOptions(int format)](#getImportOptions-int-) | Get the  ImportOptions  for specified import format. |
### produce(InputStream inputStream, int format, OutputStream outputStream) {#produce-java.io.InputStream-int-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, int format, OutputStream outputStream)
```


Produce the PDF stream using specified import format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input stream. |
| format | int | Import format. |
| outputStream | java.io.OutputStream | Output PDF stream. |

### produce(String inputFileName, int format, OutputStream outputStream) {#produce-java.lang.String-int-java.io.OutputStream-}
```
public static void produce(String inputFileName, int format, OutputStream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| format | int |  |
| outputStream | java.io.OutputStream |  |

### produce(InputStream inputStream, int format, String outputFileName) {#produce-java.io.InputStream-int-java.lang.String-}
```
public static void produce(InputStream inputStream, int format, String outputFileName)
```


Produce the PDF file using specified import format.

--------------------

```
This sample shows how to produce Pdf file from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream);
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input stream. |
| format | int | Import format. |
| outputFileName | java.lang.String | Output PDF file |

### produce(String inputFileName, int format, String outputFileName) {#produce-java.lang.String-int-java.lang.String-}
```
public static void produce(String inputFileName, int format, String outputFileName)
```


Produce the PDF file using specified import format.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String | Input file name. |
| format | int | Import format. |
| outputFileName | java.lang.String | Output PDF file |

### produce(String inputFileName, ImportOptions options, OutputStream outputStream) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(String inputFileName, ImportOptions options, OutputStream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | java.io.OutputStream |  |

### produce(InputStream inputStream, ImportOptions options, String outputFileName) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(InputStream inputStream, ImportOptions options, String outputFileName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputFileName | java.lang.String |  |

### produce(String inputFileName, ImportOptions options, String outputFileName) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(String inputFileName, ImportOptions options, String outputFileName)
```


Produce the PDF file using specified import option.

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 PdfProducer.produce(inputStream, importOptions, outputStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileName | java.lang.String | Input file name. |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Import option. |
| outputFileName | java.lang.String | Output PDF stream. |

### produce(InputStream inputStream, ImportOptions options, OutputStream outputStream) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)
```


Produce the PDF file using specified import option.

--------------------

```
This sample shows how to produce Pdf stream from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, importOptions, outputStream);
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input stream. |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Import option. |
| outputStream | java.io.OutputStream | Output PDF stream. |

### produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream) {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
```
public static void produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

### getProducer(ImportOptions options) {#getProducer-com.aspose.pdf.ImportOptions-}
```
public static PdfProducer getProducer(ImportOptions options)
```


Get the producer for specified import option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | Import option |

**Returns:**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) - PDF producer.
### getProducer(int format) {#getProducer-int-}
```
public static PdfProducer getProducer(int format)
```


Get the producer for specified import format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | Import option |

**Returns:**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) - PDF producer.
### getImportOptions(int format) {#getImportOptions-int-}
```
public static ImportOptions getImportOptions(int format)
```


Get the  ImportOptions  for specified import format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | Import format. |

**Returns:**
[ImportOptions](../../com.aspose.pdf/importoptions) - Import option.
