---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili kelas untuk menghasilkan PDF dari format lain. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\"myImage.cgm\\\"; String."
type: docs
weight: 590
url: /id/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Mewakili kelas untuk menghasilkan PDF dari format lain. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Dapatkan {@code ImportOptions} untuk format impor yang ditentukan. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Dapatkan produsen untuk format impor yang ditentukan. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Dapatkan produsen untuk opsi impor yang ditentukan. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Hasilkan aliran PDF menggunakan format impor yang ditentukan. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Hasilkan file PDF menggunakan format impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Hasilkan file PDF menggunakan opsi impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Hasilkan file PDF menggunakan format impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Hasilkan file PDF menggunakan opsi impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Dapatkan {@code ImportOptions} untuk format impor yang ditentukan.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Dapatkan produsen untuk format impor yang ditentukan.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Dapatkan produsen untuk opsi impor yang ditentukan.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Hasilkan aliran PDF menggunakan format impor yang ditentukan.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Hasilkan file PDF menggunakan format impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Hasilkan file PDF menggunakan opsi impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Hasilkan file PDF menggunakan format impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Hasilkan file PDF menggunakan opsi impor yang ditentukan. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
