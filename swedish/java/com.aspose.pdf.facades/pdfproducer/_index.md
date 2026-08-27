---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar en klass för att producera PDF från andra format. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\\\\\"myImage.cgm\\\\\\\"; String.</pre>"
type: docs
weight: 590
url: /sv/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Representerar en klass för att skapa PDF från andra format. </p> <hr> <pre>Detta exempel visar hur man producerar en Pdf-fil från en CGM-fil. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Lyckad skapad pdf-fil. } catch (Exception e) { // Gör något... } </pre>

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Hämta {@code ImportOptions} för angivet importformat. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Hämta producenten för angivet importformat. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Hämta producenten för angivet importalternativ. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Producera PDF-strömmen med angivet importformat.</p> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Skapa PDF-filen med angivet importformat. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-ström. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Skapa PDF-filen med angivet importalternativ. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-ström från en CGM-ström. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Skapa PDF-filen med angivet importformat. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-fil. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Skapa PDF-filen med angivet importalternativ. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-fil. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Hämta {@code ImportOptions} för angivet importformat.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Hämta producenten för angivet importformat.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Hämta producenten för angivet importalternativ.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Producera PDF-strömmen med angivet importformat.</p>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Skapa PDF-filen med angivet importformat. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-ström. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Skapa PDF-filen med angivet importalternativ. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-ström från en CGM-ström. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Skapa PDF-filen med angivet importformat. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-fil. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Skapa PDF-filen med angivet importalternativ. </p> <hr> <pre>Detta exempel visar hur man skapar en Pdf-fil från en CGM-fil. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
