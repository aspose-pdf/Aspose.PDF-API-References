---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverterクラス。PDFファイルの各ページを画像に変換するクラスを表します。現在、BMP、JPEG、PNG、およびTIFFをサポートしています。PDF内でサポートされているコンテンツ：画像、フォーム、コメント。
type: docs
weight: 4440
url: /ja/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverterクラス

PDFファイルの各ページを画像に変換するクラスを表し、現在BMP、JPEG、PNG、およびTIFFをサポートしています。PDF内でサポートされているコンテンツ：画像、フォーム、コメント。

```csharp
public sealed class PdfConverter : Facade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | 新しい`PdfConverter`オブジェクトを初期化します。 |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | *document*に基づいて新しい`PdfConverter`オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | ページの座標タイプ（メディア/クロップボックス）を取得または設定します。デフォルトではCropBoxの値が使用されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | 変換したい終了位置を取得または設定します。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | フォームのプレゼンテーションモードを取得または設定します。 |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | ページ数を取得します。 |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | ドキュメントのOwnerPasswordを取得または設定します。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | 変換中の解像度を取得または設定します。解像度が高いほど、変換速度は遅くなります。デフォルト値は150です。 |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | 変換したい開始位置を取得または設定します。最小値は1です。 |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | ドキュメントのUserPasswordを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | 変換のためにPDFストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | 変換のためにPDFファイルをバインドします。 |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | PdfConverterのインスタンスを閉じ、リソースを解放します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | PDFドキュメントを画像に変換するための初期作業を行います。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | デフォルトの画像形式（JPEG）でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | デフォルトの画像形式（JPEG）でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | 指定された画像形式でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | 指定されたページサイズでストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | 指定された画像形式でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | デフォルトの画像形式（JPEG）で指定されたページサイズのファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | 指定された画像形式と品質でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | 指定されたページサイズでストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | 指定された画像形式と品質でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | 指定されたページサイズと画像形式でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | 指定された画像形式、サイズ、品質でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | 指定されたページサイズ、画像形式、品質でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | 指定された画像形式と寸法でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | 指定されたページサイズ、画像形式、品質でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | 指定された画像形式、サイズ、品質でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | 指定された画像形式、寸法、品質でストリームに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | 指定された画像形式、画像サイズ、品質でファイルに画像を保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | 指定された画像形式、寸法、品質でファイルに画像を保存します。 |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | PDFファイルにさらに画像があるかどうかを示します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | ページサイズを指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | ページサイズを指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | ページサイズを指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | ページサイズを指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFストリームに保存します。 |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | 寸法を指定してPDFドキュメントの各ページを画像に変換し、画像を単一のTIFFファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFストリームに保存します。 |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | PDFドキュメントの各ページを画像に変換し、画像を単一のTIFF ClassFファイルに保存します。 |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | 画像ストリームのリストを1つの画像ストリームとしてマージします。PNG/JPG/TIFF出力形式がサポートされており、サポートされていない形式を使用する場合、出力ストリームはデフォルトでJPEGとしてエンコードされます。 |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | TIFFストリームのリストを1つの複数フレームTIFFストリームとしてマージします。 |

### 参照

* クラス [Facade](../facade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)