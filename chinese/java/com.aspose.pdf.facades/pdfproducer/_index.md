---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示一个用于从其他格式生成 PDF 的类。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\"myImage.cgm\\\"; String.</pre>"
type: docs
weight: 590
url: /zh/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> 表示用于从其他格式生成 PDF 的类。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## 方法

| 方法 | 描述 |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | 获取指定导入格式的 {@code ImportOptions}。 |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | 获取指定导入格式的生产者。 |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | 获取指定导入选项的生产者。 |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> 使用指定的导入格式生成 PDF 流。</p> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> 使用指定的导入格式生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> 使用指定的导入选项生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> 使用指定的导入格式生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> 使用指定的导入选项生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
获取指定导入格式的 {@code ImportOptions}。

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
获取指定导入格式的生产者。

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
获取指定导入选项的生产者。

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> 使用指定的导入格式生成 PDF 流。</p>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> 使用指定的导入格式生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> 使用指定的导入选项生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> 使用指定的导入格式生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> 使用指定的导入选项生成 PDF 文件。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
