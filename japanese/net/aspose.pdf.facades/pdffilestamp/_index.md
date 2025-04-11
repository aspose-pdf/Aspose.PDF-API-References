---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStampクラス。PDFファイルにスタンプ、透かし、または背景を追加するためのクラス
type: docs
weight: 4570
url: /ja/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStampクラス

PDFファイルにスタンプ（透かしまたは背景）を追加するためのクラス。

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | PdfFileStampのコンストラクタ。入力ファイルと出力ファイルは、対応するプロパティを介して指定できます。 |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | *document*に基づいて新しい`PdfFileStamp`オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | PDFファイル形式を設定します。結果ファイルは指定されたファイル形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトのPDF形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | ドキュメントファサードが作業しているものを取得します。 |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | trueの場合、セキュリティを保持します。（この機能は次のバージョンで実装されます）。 |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | ページ番号スタイルを取得または設定します。可能な値：NumeralsArabic、NumeralsRomanUppercase、NumeralsRomanLowercase、LettersAppercase、LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同等のリソースストリームは1つのPDFオブジェクトにマージされます。これにより、結果ファイルのサイズを減少させることができますが、実行速度が遅くなり、メモリ要件が大きくなる可能性があります。デフォルト値：false。 |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | ソースファイルの最初のページの高さを取得します。 |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | ページ番号の回転を取得または設定します。回転は度単位です。デフォルトは0です。 |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | 入力ファイルの最初のページの幅を取得します。 |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | 次に追加されるスタンプのスタンプID（ページヘッダー/フッター/ページ番号を含む）。 |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | 入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号が付けられます。たとえば、StartingNumberが100に設定されている場合、ドキュメントのページには100、101、102...という番号が付けられます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | ドキュメントのページにフッターを追加します。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | ページのフッターとして画像を追加します。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | ドキュメントのページにフッターとして画像を追加します。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | ドキュメントのページにフッターを追加します。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | ページのフッターとして画像を追加します。 |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | ページのフッターとして画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | ページにヘッダーを追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | ページに画像をヘッダーとして追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | ファイルのページにヘッダーとして画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | ファイルのページにヘッダーを追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | ページの上部に画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | ページに画像をヘッダーとして追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | ページにページ番号を追加します。ページ番号には#記号が含まれており、ページ番号に置き換えられます。ページ番号はページの下部に水平に中央揃えで配置されます。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | ファイルにページ番号を追加します。ページ番号テキストには#記号が含まれており、ページの番号に置き換えられます。ページ番号はページの下部に水平に中央揃えで配置されます。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | ページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | ページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | 指定された位置にページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | 指定された位置にページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | ドキュメントのページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | ドキュメントのページにページ番号を追加します。 |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | ファイルにスタンプを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | 開いているファイルを閉じて変更を保存します。警告：入力または出力ストリームが指定されている場合、Close()メソッドによってそれらは閉じられません。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | ドキュメントを指定されたストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | 結果を指定されたファイルに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | 左下の位置。 |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | 下中央の位置。 |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | 右下の位置。 |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | 左の位置。 |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | 右の位置。 |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | 左上の位置。 |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | 上中央の位置。 |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | 右上の位置。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)