---
title: "PdfExtractor クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfExtractor クラス。PDF ドキュメントから画像とテキストを抽出するクラス"
type: docs
weight: 4570
url: /ja/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

PDF ドキュメントから画像とテキストを抽出するクラスです。

```csharp
public sealed class PdfExtractor : Facade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | 新しい `PdfExtractor` オブジェクトを初期化します。 |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | *document* を基に新しい `PdfExtractor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | 抽出操作が実行されるページ範囲の終了ページを取得または設定します。 |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | 画像抽出プロセスのモードを設定します。 |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | テキスト抽出結果のモードを設定します。 |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | テキストにヘブライ語またはアラビア語の記号が含まれる場合に true になります。このケースは、文字列関数の動作が変わり、テキストの処理が右から左へ（数字やその他の非テキスト文字は除く）開始されるため、特別に考慮する必要があります。 |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | 入力ファイルのパスワードを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | 抽出された画像の解像度を設定または取得します。デフォルト値は150です。解像度の値が大きい画像はより鮮明になります。ただし、解像度の値を上げると画像抽出に必要な時間とメモリが増加します。通常、鮮明な画像を得るには解像度を150または300に設定すれば十分です。 |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | 抽出操作が実行されるページ範囲内の開始ページを取得または設定します。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | ストリームからPDFドキュメントをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | 入力PDFファイルをバインドします。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Pdfドキュメントから添付ファイルを抽出します。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | 添付名でPDFファイルから添付ファイルを抽出します。 |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | PDFファイルから画像を抽出します。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Unicodeエンコーディングを使用してPdfドキュメントからテキストを抽出します。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | 指定されたエンコーディングを使用してPdfドキュメントからテキストを抽出します。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | すべての添付ファイルをストリームに保存します。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | 添付ファイルをファイルに保存します。 |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | 添付ファイルの一覧を取得します。 |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | PDFファイル内の添付ファイル一覧を返します。注: このメソッドを使用する前にExtractAttachmentsを呼び出す必要があります。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | PDFファイルから次の画像を取得し、ストリームに保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | PDFドキュメントから次の画像を取得します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | PDFファイルから次の画像を取得し、指定された画像形式でストリームに保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | PDFドキュメントから次の画像を取得し、指定された画像形式で保存します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | 1ページ分のテキストをストリームに保存します。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | 1ページ分のテキストをファイルに保存します。 |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | テキストをストリームに保存します。参照:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | テキストをファイルに保存します。参照:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | テキストをストリームに保存します。参照:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | PDFドキュメントでさらに画像が取得可能か確認します。注: このメソッドを使用する前にExtractImageを呼び出す必要があります。 |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | さらにテキストを取得できるかどうかを示します。 |

### 関連項目

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


