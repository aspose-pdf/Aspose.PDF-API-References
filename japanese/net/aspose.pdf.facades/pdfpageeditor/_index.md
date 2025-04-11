---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor クラス。ページの回転、ズーム、位置の移動、ページサイズの変更を含む PDF ファイルのページを編集するためのクラスを表します。
type: docs
weight: 4590
url: /ja/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor クラス

PDF ファイルのページを編集するためのクラスを表します。これには、ページの回転、ページのズーム、位置の移動、ページサイズの変更が含まれます。

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | PdfPageEditor クラスのコンストラクタ。 |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | PdfPageEditor クラスのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | ページの表示時間を取得または設定します。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | 結果ページ上の元の PDF コンテンツの水平方向の配置を取得または設定します。デフォルトは AlignmentType.Left です。 |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | ページ番号と回転角度を含むハッシュテーブル。キーはページ番号を表し、キーの値は度数での回転を表します。 |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | 出力ファイルのページサイズを取得または設定します。 |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | 編集するページ番号を取得または設定します。デフォルトでは、各ページが編集されます。 |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | ページの回転を取得または設定します。回転は 0、90、180、または 270 でなければなりません。デフォルト値は 0 です。 |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | トランジション効果の持続時間を取得または設定します。 |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | プレゼンテーション中に別のページからこのページに移動する際に使用するトランジションスタイルを取得または設定します。 |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | 結果ページ上の元の PDF コンテンツの垂直方向の配置を取得または設定します。デフォルトは VerticalAlignmentType.Bottom です。 |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | ズーム係数を取得または設定します。値 1.0 は 100% に対応します。デフォルト値は 1.0 です。以下の例は、ドキュメントページのズームを変更する方法を示しています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | ドキュメントページに加えた変更を適用します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | ドキュメント内の指定されたボックスのサイズを返します。 |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | 指定されたページの回転を返します。 |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | 総ページ数を返します。 |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | 指定されたページのページサイズを返します。 |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | 原点を (0, 0) から指定された点に移動します。原点は左下で、単位はポイント (1 インチ = 72 ポイント) です。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | 変更されたドキュメントをストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | 変更されたドキュメントをファイルに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | 垂直ブラインド |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | 垂直ブラインド |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | 下から上へのワイプ |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | 対角グリッター |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | 古いページが溶ける |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | 内向きボックス |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | 左から右へのグリッター |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | 左から右へのワイプ |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | 外向きボックス |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | 右から左へのワイプ |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | 内部水平分割 |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | 外部水平分割 |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | 内部垂直分割 |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | 外部垂直分割 |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | 上から下へのグリッター |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | 上から下へのワイプ |

### 参照

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)