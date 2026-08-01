---
title: "クラス PdfContentEditor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfContentEditor クラス。PDFファイルのコンテンツを編集するクラスを表します。"
type: docs
weight: 4550
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

PDF ファイルのコンテンツを編集するクラスを表します。

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | PdfContentEditor オブジェクトのコンストラクタ。 |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | 新しい `PdfContentEditor` オブジェクトを *document* を基に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | テキスト置換操作のパラメータセット |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。 |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | テキスト置換オプションを取得または設定します。 |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | ドキュメントイベントに対して追加のアクションを追加します。 |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | 注釈なしでドキュメント添付ファイルを追加します。 |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | 注釈なしでドキュメント添付ファイルを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | 編集用に PDF ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | 編集用に PDF ファイルをバインドします。 |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | ビュー設定を変更します。 |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | 開かれたドキュメントを閉じます。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | PDF ドキュメント内でアプリケーションを起動するリンクを作成します。 |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | 指定されたアクションを持つブックマークを作成します。 |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | キャレット注釈を作成します。 |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | PDF ドキュメント内のカスタムアクションへのリンクを作成します。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | ファイル添付注釈を作成します。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | ファイル添付注釈を作成します。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | ファイル添付注釈を作成します。 |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | ファイル添付注釈を作成します。 |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | PDF ドキュメントにフリーテキスト注釈を作成します |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | PDF ドキュメント内の JavaScript へのリンクを作成します。 |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | 線注釈を作成します。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | PDF ドキュメント内にローカルリンクを作成します。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | PDF ドキュメント内にローカルリンクを作成します。 |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | PDF ドキュメント内にローカルリンクを作成します。 |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | PDF ドキュメントにマークアップ注釈を作成します。 |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | ムービー注釈を作成します。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | 別の PDF ドキュメントページへのリンクを作成します。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | 別の PDF ドキュメントページへのリンクを作成します。 |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | 別の PDF ドキュメントページへのリンクを作成します。 |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | ポリゴン注釈を作成します。 |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | ポリライン注釈を作成します。 |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | PDFドキュメントにポップアップ注釈を作成します。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | ゴムスタンプ注釈を作成します。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | ゴムスタンプ注釈を作成します。 |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | ゴムスタンプ注釈を作成します。 |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | サウンド注釈を作成します。 |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | 四角形・円形注釈を作成します。 |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | PDFドキュメントにテキスト注釈を作成します |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | PDFドキュメントにウェブリンクを作成します。 |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | PDFドキュメントにウェブリンクを作成します。 |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | PDFドキュメントにウェブリンクを作成します。 |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | PDFドキュメント内のすべての添付ファイルを削除します。 |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | PDFドキュメントからすべての画像を削除します。 |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | 指定されたページ上の指定された画像を削除します。 |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | 指定されたページ上でスタンプインデックスで複数のスタンプを削除します。 |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | ドキュメントのすべてのページからIDでスタンプを削除します。 |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | 指定されたページ上でスタンプIDによりスタンプを削除します。 |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | ドキュメントのすべてのページから指定されたIDのスタンプを削除します。 |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | 指定されたページ上で複数のスタンプIDによりスタンプを削除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | 曲線注釈を作成します。 |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | PDFドキュメントに含まれるLinkインスタンスのコレクションを抽出します。 |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | ページ上のスタンプ配列を返します。 |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | 表示設定を返します。 |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | スタンプを非表示にします。非表示にした後、スタンプの表示は ShowStampById メソッドで復元できる場合があります。 |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | ページ上のスタンプの位置を変更します。 |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | ページ上のスタンプの位置を変更します。 |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | ドキュメントからオープンアクションを削除します。この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを連結する際に便利です。 |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | PDFドキュメントの指定されたページ上の指定された画像を別の画像に置き換えます。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | PDFファイル内のテキストを置き換えます。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | 指定されたページの PDF ファイル内のテキストを置き換えます。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | PDF ファイル内のテキストを置換し、フォントサイズを設定します。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | 指定された [`TextState`](../../aspose.pdf.text/textstate/) オブジェクトを使用して、PDF ファイル内のテキストを置換します。 |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | 指定ページの PDF ファイル内のテキストを置換します。置換するテキストに対して、[`TextState`](../../aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、カラー）を指定できます。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | HiddenStampById によって非表示にされたスタンプを表示します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | Document のイベントタイプです。Document を閉じます。 |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | Document のイベントタイプです。Document を開きます。 |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | Document のイベントタイプです。印刷後にアクションを実行します。 |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | Document のイベントタイプです。保存後にアクションを実行します。 |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | Document のイベントタイプです。印刷前にアクションを実行します。 |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | Document のイベントタイプです。保存前にアクションを実行します。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


