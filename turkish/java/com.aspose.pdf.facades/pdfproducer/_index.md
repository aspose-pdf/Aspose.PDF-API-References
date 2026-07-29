---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Diğer formatlardan PDF üretmek için bir sınıfı temsil eder. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\\\\\"myImage.cgm\\\\\\\"; String."
type: docs
weight: 590
url: /tr/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Diğer formatlardan PDF üretmek için bir sınıfı temsil eder. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Belirtilen içe aktarma formatı için {@code ImportOptions} alın. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Belirtilen içe aktarma formatı için üreticiyi alın. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Belirtilen içe aktarma seçeneği için üreticiyi alın. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Belirtilen içe aktarma formatını kullanarak PDF akışını üret. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Belirtilen içe aktarma formatını kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Belirtilen içe aktarma formatını kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Belirtilen içe aktarma formatı için {@code ImportOptions} alın.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Belirtilen içe aktarma formatı için üreticiyi alın.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Belirtilen içe aktarma seçeneği için üreticiyi alın.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Belirtilen içe aktarma formatını kullanarak PDF akışını üret.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Belirtilen içe aktarma formatını kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Belirtilen içe aktarma formatını kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üret. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
