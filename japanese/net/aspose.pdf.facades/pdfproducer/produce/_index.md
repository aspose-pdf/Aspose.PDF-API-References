---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer メソッド。指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは、CGM ストリームから PDF ストリームを生成する方法を示しています。
type: docs
weight: 10
url: /ja/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは、CGM ストリームから PDF ストリームを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| format | ImportFormat | インポート形式。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 入力または出力ストリームが null |

### 参照

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは、CGM ファイルから PDF ストリームを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileName | String | 入力ファイル名。 |
| format | ImportFormat | インポート形式。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 出力ストリームが null |
| ArgumentException | 入力ファイル名が空の文字列 |

### 参照

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| format | ImportFormat | インポート形式。 |
| outputFileName | String | 出力 PDF ファイル |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 入力ストリームが null |
| ArgumentException | 出力ファイル名が空の文字列 |

### 参照

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileName | String | 入力ファイル名。 |
| format | ImportFormat | インポート形式。 |
| outputFileName | String | 出力 PDF ファイル |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentException | 入力または出力ファイル名が空の文字列 |

### 参照

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

指定されたインポートオプションを使用して PDF ストリームを生成します。このサンプルは、CGM ファイルから PDF ストリームを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, importOptions, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileName | String | 入力ファイル名。 |
| options | ImportOptions | インポートオプション。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 出力ストリームが null |
| ArgumentException | 入力ファイル名が空の文字列 |

### 参照

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputFile);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| options | ImportOptions | インポートオプション。 |
| outputFileName | String | 出力 PDF ファイル。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 入力ストリームが null |
| ArgumentException | 出力ファイル名が空の文字列 |

### 参照

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFileName | String | 入力ファイル名。 |
| options | ImportOptions | インポートオプション。 |
| outputFileName | String | 出力 PDF ストリーム。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentException | 入力または出力ファイル名が空の文字列 |

### 参照

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ストリームを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| options | ImportOptions | インポートオプション。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | ファイルが無効な場合に例外がスローされます。 |
| ArgumentNullException | 入力または出力ストリームが null。 |

### 参照

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)