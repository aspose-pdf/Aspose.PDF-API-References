---
title: "PdfProducer"
linktitle: "PdfProducer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> 他の形式から PDF を生成するクラスを表します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = \\\"myImage.cgm\\\"; String."
type: docs
weight: 590
url: /ja/java/com.aspose.pdf.facades/pdfproducer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfProducer

```
public abstract class PdfProducer extends Object
```

<p> 他の形式から PDF を生成するクラスを表します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre>

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImportOptions](#getImportOptions-com.aspose.pdf.ImportFormat-) | 指定されたインポート形式の {@code ImportOptions} を取得します。 |
| [getProducer](#getProducer-com.aspose.pdf.ImportFormat-) | 指定されたインポート形式のプロデューサーを取得します。 |
| [getProducer](#getProducer-com.aspose.pdf.ImportOptions-) | 指定されたインポートオプションのプロデューサーを取得します。 |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-) | <p> 指定されたインポート形式を使用して PDF ストリームを生成します. |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> 指定されたインポート形式を使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | <p> 指定されたインポートオプションを使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre> |
| [produce](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-) | <p> 指定されたインポート形式を使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre> |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | <p> 指定されたインポートオプションを使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre> |
| [produceInternal](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |

### getImportOptions {#getImportOptions-com.aspose.pdf.ImportFormat-}
指定されたインポート形式の {@code ImportOptions} を取得します。

### getProducer {#getProducer-com.aspose.pdf.ImportFormat-}
指定されたインポート形式のプロデューサーを取得します。

### getProducer {#getProducer-com.aspose.pdf.ImportOptions-}
指定されたインポートオプションのプロデューサーを取得します。

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.io.OutputStream-}
<p> 指定されたインポート形式を使用して PDF ストリームを生成します.

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> 指定されたインポート形式を使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
<p> 指定されたインポートオプションを使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf stream from CGM stream. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); using (FileInputStream inputStream = File.OpenRead(inputFile)) using (FileOutputStream outputStream = File.Create(outputFile)) { PdfProducer.produce(inputStream, importOptions, outputStream); } </pre>

### produce {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportFormat-java.lang.String-}
<p> 指定されたインポート形式を使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); </pre>

### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}


### produce {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
<p> 指定されたインポートオプションを使用して PDF ファイルを生成します。 </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; ImportOptions importOptions = new CgmImportOptions(); PdfProducer.produce(inputStream, importOptions, outputStream); </pre>

### produceInternal {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
