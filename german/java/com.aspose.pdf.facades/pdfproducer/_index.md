---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt eine Klasse dar, die PDF aus anderen Formaten erzeugt. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\\\"myImage.cgm\\\"; String.</pre>"
type: docs
weight: 590
url: /de/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Stellt eine Klasse dar, um PDF aus anderen Formaten zu erzeugen. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Rufen Sie die {@code ImportOptions} für das angegebene Importformat ab. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Rufen Sie den Produzenten für das angegebene Importformat ab. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Rufen Sie den Produzenten für die angegebene Importoption ab. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Erzeugen Sie den PDF-Stream mit dem angegebenen Importformat.</p> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Rufen Sie die {@code ImportOptions} für das angegebene Importformat ab.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Rufen Sie den Produzenten für das angegebene Importformat ab.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Rufen Sie den Produzenten für die angegebene Importoption ab.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Erzeugen Sie den PDF-Stream mit dem angegebenen Importformat.</p>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
