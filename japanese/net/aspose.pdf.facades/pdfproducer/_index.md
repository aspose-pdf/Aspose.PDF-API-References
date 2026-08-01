---
title: "クラス PdfProducer"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfProducer クラス。他の形式から PDF を生成するクラスを表します。このサンプルは CGM ファイルから Pdf ファイルを生成する方法を示しています。"
type: docs
weight: 4730
url: /ja/net/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class

他の形式から PDF を生成するクラスを表します。このサンプルは CGM ファイルから Pdf ファイルを生成する方法を示しています。

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
try
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
    // pdf ファイルの生成に成功しました。
}
catch (InvalidCgmFileFormatException e)
{
    //  何かを実行します…
}
```

```csharp
public abstract class PdfProducer
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce)(Stream, ImportFormat, Stream) | 指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは CGM ストリームから Pdf ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_1)(Stream, ImportFormat, string) | 指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは CGM ストリームから Pdf ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_2)(Stream, ImportOptions, Stream) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは CGM ストリームから Pdf ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_3)(Stream, ImportOptions, string) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは CGM ストリームから Pdf ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_4)(string, ImportFormat, Stream) | 指定されたインポート形式を使用して PDF ストリームを生成します。このサンプルは CGM ファイルから Pdf ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_5)(string, ImportFormat, string) | 指定されたインポート形式を使用して PDF ファイルを生成します。このサンプルは CGM ファイルから Pdf ファイルを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_6)(string, ImportOptions, Stream) | 指定されたインポートオプションを使用して PDF ストリームを生成します。このサンプルは CGM ファイルから Pdf ストリームを生成する方法を示しています。 |
| static [Produce](../../aspose.pdf.facades/pdfproducer/produce/#produce_7)(string, ImportOptions, string) | 指定されたインポートオプションを使用して PDF ファイルを生成します。このサンプルは CGM ファイルから PDF ファイルを生成する方法を示しています。 |

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


