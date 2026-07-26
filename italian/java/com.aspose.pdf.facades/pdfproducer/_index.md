---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta una classe per generare PDF da altri formati. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\\\\\"myImage.cgm\\\\\\\"; String.</pre>"
type: docs
weight: 590
url: /it/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Rappresenta una classe per generare PDF da altri formati. </p> <hr> <pre>Questo esempio mostra come produrre un file Pdf da un file CGM. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Ottieni il {@code ImportOptions} per il formato di importazione specificato. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Ottieni il produttore per il formato di importazione specificato. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Ottieni il produttore per l'opzione di importazione specificata. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Genera lo stream PDF utilizzando il formato di importazione specificato.</p> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Genera il file PDF utilizzando il formato di importazione specificato. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Genera il file PDF utilizzando l'opzione di importazione specificata. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Genera il file PDF utilizzando il formato di importazione specificato. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Genera il file PDF utilizzando l'opzione di importazione specificata. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Ottieni il {@code ImportOptions} per il formato di importazione specificato.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Ottieni il produttore per il formato di importazione specificato.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Ottieni il produttore per l'opzione di importazione specificata.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Genera lo stream PDF utilizzando il formato di importazione specificato.</p>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Genera il file PDF utilizzando il formato di importazione specificato. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Genera il file PDF utilizzando l'opzione di importazione specificata. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Genera il file PDF utilizzando il formato di importazione specificato. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Genera il file PDF utilizzando l'opzione di importazione specificata. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
