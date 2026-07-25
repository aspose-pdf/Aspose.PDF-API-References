---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente une classe permettant de produire un PDF à partir d'autres formats. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\"myImage.cgm\\\"; String.</pre>"
type: docs
weight: 590
url: /fr/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Représente une classe permettant de produire un PDF à partir d'autres formats. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## Méthodes

| Méthode | Description |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Obtenez le {@code ImportOptions} pour le format d'importation spécifié. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Obtenez le producteur pour le format d'importation spécifié. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Obtenez le producteur pour l'option d'importation spécifiée. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Produisez le flux PDF en utilisant le format d'importation spécifié. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Produisez le fichier PDF en utilisant le format d'importation spécifié. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Produisez le fichier PDF en utilisant l'option d'importation spécifiée. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Produisez le fichier PDF en utilisant le format d'importation spécifié. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Produisez le fichier PDF en utilisant l'option d'importation spécifiée. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Obtenez le {@code ImportOptions} pour le format d'importation spécifié.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Obtenez le producteur pour le format d'importation spécifié.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Obtenez le producteur pour l'option d'importation spécifiée.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Produisez le flux PDF en utilisant le format d'importation spécifié.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Produisez le fichier PDF en utilisant le format d'importation spécifié. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Produisez le fichier PDF en utilisant l'option d'importation spécifiée. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Produisez le fichier PDF en utilisant le format d'importation spécifié. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Produisez le fichier PDF en utilisant l'option d'importation spécifiée. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
