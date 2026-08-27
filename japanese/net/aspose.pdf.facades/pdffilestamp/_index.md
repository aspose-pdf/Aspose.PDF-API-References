---
title: "クラス PdfFileStamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileStamp クラス。PDF ファイルにスタンプ、透かし、または背景を追加するためのクラスです。"
type: docs
weight: 4690
url: /ja/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

PDF ファイルにスタンプ（透かしまたは背景）を追加するクラスです。

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | PdfFileStamp のコンストラクタ。入力ファイルと出力ファイルは対応するプロパティで指定できます。 |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | 新しい `PdfFileStamp` オブジェクトを *document* を基に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | true の場合、セキュリティを保持します。（この機能は次のバージョンで実装される予定です）。 |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | ページ番号付けスタイルを取得または設定します。可能な値: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | 最適化フラグを取得または設定します。このフラグが設定されている場合、結果ファイル内の同一リソースストリームは 1 つの PDF オブジェクトにマージされます。これにより結果ファイルのサイズを減らすことができますが、実行が遅くなりメモリ使用量が増加する可能性があります。デフォルト値: false。 |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | ソースファイルの最初のページの高さを取得します。 |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | ページ番号の回転を取得または設定します。回転は度数で指定します。デフォルトは 0 です。 |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | 入力ファイルの最初のページの幅を取得します。 |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | 次に追加されるスタンプのスタンプ ID（ページヘッダー/フッター/ページ番号を含む）。 |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | 入力ファイルの最初のページの開始番号を取得または設定します。次のページはこの値から番号付けされます。例えば StartingNumber を 100 に設定すると、ドキュメントのページ番号は 100、101、102…となります。 |

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
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | ページのヘッダーとして画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | ファイルのページのヘッダーとして画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | ファイルのページにヘッダーを追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | ページの上部に画像を追加します。 |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | ページのヘッダーとして画像を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | ページにページ番号を追加します。ページ番号には # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページの下部に水平中央に配置されます。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | ファイルにページ番号を追加します。ページ番号のテキストには # 記号を含めることができ、# はページ番号に置き換えられます。ページ番号はページの下部に水平中央に配置されます。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | ページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | ページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | ページ上の指定位置にページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | ページ上の指定位置にページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | ドキュメントのページにページ番号を追加します。 |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | ドキュメントのページにページ番号を追加します。 |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | ファイルにスタンプを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | 開いているファイルを閉じ、変更を保存します。警告: 入力または出力ストリームが指定されている場合、Close() メソッドではそれらは閉じられません。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | document を指定されたストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | 結果を指定されたファイルに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | 左下位置。 |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | 下中央位置。 |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | 右下位置。 |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | 左位置。 |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | 右位置。 |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | 左上位置。 |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | 上部中央位置。 |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | 右上位置。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


