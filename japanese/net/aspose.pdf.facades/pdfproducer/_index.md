---
title: Class PdfProducer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfProducer クラス。 他の形式から PDF を生成するクラスを表します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。
type: docs
weight: 4610
url: /ja/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer クラス

他の形式から PDF を生成するクラスを表します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // Success produced pdf file.
}
catch (InvalidCgmFileFormatException e)
{
    //  Do something...
}
```

```csharp
public abstract class PdfProducer
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | 指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは、CGM ストリームから PDF ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | 指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ストリームから PDF ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | 指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは、CGM ファイルから PDF ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | 指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | 指定されたインポートオプションを使用して PDF ストリームを生成します。このサンプルは、CGM ファイルから PDF ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは、CGM ファイルから PDF ファイルを生成する方法を示しています。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)