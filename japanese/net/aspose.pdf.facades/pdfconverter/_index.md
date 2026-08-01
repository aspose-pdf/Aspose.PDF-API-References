---
title: "クラス PdfConverter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfConverter クラス。PDF ファイルの各ページを BMP、JPEG、PNG、TIFF 形式の画像に変換できるクラスを表します。PDF の画像やコメント形式のコンテンツをサポートしています。"
type: docs
weight: 4560
url: /ja/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

PDF ファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、TIFF をサポートしています。PDF のサポート対象コンテンツ：画像、フォーム、コメント。

```csharp
public sealed class PdfConverter : Facade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | `PdfConverter` オブジェクトを新規に初期化します。 |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | *document* を基に `PdfConverter` オブジェクトを新規に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | 変換したい終了位置を取得または設定します。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | フォームの表示モードを取得または設定します。 |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | ページ数を取得します。 |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | ドキュメントの OwnerPassword を取得または設定します。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | 変換時の解像度を取得または設定します。解像度が高いほど変換速度は遅くなります。既定値は 150 です。 |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | 変換したい開始位置を取得または設定します。最小値は 1 です。 |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | ドキュメントの UserPassword を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf)(Document) | PDF ドキュメントを `PdfConverter` インスタンスにバインドして、さらに処理できるようにします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | 変換用に Pdf ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | 変換用に Pdf ファイルをバインドします。 |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | PdfConverter のインスタンスを閉じ、リソースを解放します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Pdf ドキュメントを画像に変換するための初期処理を実行します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | 画像をストリームに保存します（デフォルトの画像形式 - jpeg）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | 画像をファイルに保存します（デフォルトの画像形式 - jpeg）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | 画像をストリームに保存します（指定された画像形式）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | 画像をストリームに保存します（指定されたページサイズ）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | 画像をファイルに保存します（指定された画像形式）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | 画像をファイルに保存します（指定されたページサイズとデフォルトの画像形式 - jpeg）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | 画像をストリームに保存します（指定された画像形式と品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | 画像をストリームに保存します（指定されたページサイズ）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | 画像をファイルに保存します（指定された画像形式と品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | 画像をファイルに保存します（指定されたページサイズと画像形式）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | 画像をストリームに保存します（指定された画像形式、サイズ、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | 画像をストリームに保存します（指定されたページサイズ、画像形式、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | 画像をファイルに保存します（指定された画像形式と寸法）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | 画像をファイルに保存します（指定されたページサイズ、画像形式、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | 画像をストリームに保存します（指定された画像形式、サイズ、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | 画像をストリームに保存します（指定された画像形式、寸法、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | 画像をファイルに保存します（指定された画像形式、画像サイズ、品質）。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | 画像をファイルに保存します（指定された画像形式、寸法、品質）。 |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | PDF ファイルに画像がさらにあるかどうかを示します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、ページサイズで画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | PDF ドキュメントの各ページを画像に変換し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | PDF ドキュメントの各ページを画像に変換し、寸法で画像を作成し、単一の TIFF ファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | PDF ドキュメントの各ページを画像に変換し、画像を単一の TIFF ClassF ファイルに保存します。 |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | 画像ストリームのリストを 1 つの画像ストリームに結合します。Png/jpg/tiff の出力形式がサポートされており、サポートされていない形式を使用した場合、出力ストリームはデフォルトで Jpeg としてエンコードされます。 |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | tiff ストリームのリストを 1 つの複数フレーム tiff ストリームに結合します。 |

### 関連項目

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


