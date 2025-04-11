---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor クラス。PDF ドキュメントから画像とテキストを抽出するためのクラス
type: docs
weight: 4450
url: /ja/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor クラス

PDF ドキュメントから画像とテキストを抽出するためのクラス。

```csharp
public sealed class PdfExtractor : Facade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | 新しい `PdfExtractor` オブジェクトを初期化します。 |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | *document* に基づいて新しい `PdfExtractor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | 抽出操作が実行されるページ範囲の終了ページを取得または設定します。 |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | 画像抽出プロセスのモードを設定します。 |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | テキスト抽出結果のモードを設定します。 |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | テキストにヘブライ語またはアラビア語の記号が含まれている場合は true になります。この場合、文字列関数の動作が変わり、テキストの処理が右から左に開始されます（数字やその他の非テキスト文字を除く）。 |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | 入力ファイルのパスワードを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | 抽出された画像の解像度を設定または取得します。デフォルト値は 150 です。解像度値が大きいほど画像は鮮明になります。ただし、解像度値を上げると、画像を抽出するために必要な時間とメモリが増加します。通常、鮮明な画像を得るには解像度を 150 または 300 に設定するだけで十分です。 |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | 抽出操作が実行されるページ範囲の開始ページを取得または設定します。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | ストリームから PDF ドキュメントをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | 入力 PDF ファイルをバインドします。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | PDF ドキュメントから添付ファイルを抽出します。 |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | 添付ファイル名によって PDF ファイルに添付ファイルを抽出します。 |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | PDF ファイルから画像を抽出します。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Unicode エンコーディングを使用して PDF ドキュメントからテキストを抽出します。 |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | 指定されたエンコーディングを使用して PDF ドキュメントからテキストを抽出します。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | すべての添付ファイルをストリームに保存します。 |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | 添付ファイルをファイルに保存します。 |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | 添付ファイルのリストを取得します。 |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | PDF ファイル内の添付ファイルのリストを返します。注意: このメソッドを使用する前に ExtractAttachments を呼び出す必要があります。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | PDF ファイルから次の画像を取得し、ストリームに保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | PDF ドキュメントから次の画像を取得します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | PDF ファイルから次の画像を取得し、指定された画像形式でストリームに保存します。 |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | 指定された画像形式で PDF ドキュメントから次の画像を取得します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | 1 ページのテキストをストリームに保存します。 |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | 1 ページのテキストをファイルに保存します。 |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | テキストをストリームに保存します。参照: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | テキストをファイルに保存します。参照: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | テキストをストリームに保存します。参照: [`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | PDF ドキュメントにさらに画像がアクセス可能かどうかを確認します。注意: このメソッドを使用する前に ExtractImage を呼び出す必要があります。 |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | さらにテキストを取得できるかどうかを示します。 |

### 参照

* クラス [Facade](../facade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)