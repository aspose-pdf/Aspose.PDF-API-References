---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor クラス。PDF ファイルのブックマークを作成、変更、エクスポート、インポート、削除するためのクラスを表します。
type: docs
weight: 4420
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor クラス

PDF ファイルのブックマークを作成、変更、エクスポート、インポート、削除するためのクラスを表します。

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | 新しい `PdfBookmarkEditor` オブジェクトを初期化します。 |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | *document* に基づいて新しい `PdfBookmarkEditor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | 指定されたページのブックマークを作成します。 |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | 指定されたページのブックマークを作成します。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | すべてのページのブックマークを作成します。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | ドキュメント内に指定されたブックマークを作成します。このメソッドは、ネストされたブックマーク階層を形成するために使用できます。 |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | 指定された色とスタイル（太字、斜体）で、すべてのページのブックマークを作成します。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | PDF ドキュメントのすべてのブックマークを削除します。 |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | PDF ドキュメントのブックマークを削除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | ブックマークを XML ストリームにエクスポートします。 |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | ブックマークを XML ファイルにエクスポートします。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | 指定されたブックマークと同じタイトルのブックマークの子を抽出します。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | ドキュメントからすべてのレベルのブックマークを抽出します。 |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | 指定されたタイトルのブックマークを抽出します。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | XML ファイルからドキュメントにブックマークをインポートします。 |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | XML ファイルからドキュメントにブックマークをインポートします。 |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | 指定されたブックマークタイトルに従ってブックマークタイトルを変更します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | ブックマークを HTML ファイルにエクスポートします。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)