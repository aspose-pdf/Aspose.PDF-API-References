---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa una clase para generar PDF a partir de otros formatos. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\"myImage.cgm\\\"; String."
type: docs
weight: 590
url: /es/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> Representa una clase para generar PDF a partir de otros formatos. </p> <hr> <pre>Este ejemplo muestra cómo generar un archivo Pdf a partir de un archivo CGM. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Archivo pdf generado con éxito. } catch (Exception e) { // Hacer algo... } </pre>

## Métodos

| Método | Descripción |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | Obtenga el {@code ImportOptions} para el formato de importación especificado. |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | Obtenga el productor para el formato de importación especificado. |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | Obtenga el productor para la opción de importación especificada. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> Produce la secuencia PDF usando el formato de importación especificado. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Produce el archivo PDF usando el formato de importación especificado. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> Produce el archivo PDF usando la opción de importación especificada. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> Produce el archivo PDF usando el formato de importación especificado. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> Produce el archivo PDF usando la opción de importación especificada. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
Obtenga el {@code ImportOptions} para el formato de importación especificado.

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
Obtenga el productor para el formato de importación especificado.

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
Obtenga el productor para la opción de importación especificada.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> Produce la secuencia PDF usando el formato de importación especificado.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Produce el archivo PDF usando el formato de importación especificado. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> Produce el archivo PDF usando la opción de importación especificada. </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> Produce el archivo PDF usando el formato de importación especificado. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> Produce el archivo PDF usando la opción de importación especificada. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
