---
title: "クラス PdfPageEditor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfPageEditor クラス。PDF ファイルのページを編集するクラスを表し、ページの回転、ズーム、位置の移動、ページサイズの変更などを含みます。"
type: docs
weight: 4710
url: /ja/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

PDF ファイルのページを編集するクラスを表します。ページの回転、ズーム、位置の移動、ページサイズの変更を含みます。

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | 結果ページ上の元の PDF コンテンツの水平位置揃えを取得または設定します。デフォルトは AlignmentType.Left です。 |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | ハッシュテーブルにはページ番号と回転角度が含まれ、キーがページ番号を表し、キーの値が回転角度（度）を表します。 |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | 出力ファイルのページサイズを取得または設定します。 |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | 編集対象のページ番号を取得または設定します。デフォルトでは、すべてのページが編集されます。 |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | ページの回転を取得または設定します。回転は 0、90、180、または 270 のいずれかでなければなりません。デフォルト値は 0 です。 |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | トランジション効果の期間を取得または設定します。 |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | プレゼンテーション中に別のページからこのページへ移動する際に使用するトランジションスタイルを取得または設定します。 |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | 結果ページ上の元の PDF コンテンツの垂直位置揃えを取得または設定します。デフォルトは VerticalAlignmentType.Bottom です。 |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | ズーム係数を取得または設定します。値 1.0 は 100% に相当します。デフォルト値は 1.0 です。以下の例は Document ページのズームを変更する方法を示しています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Document のページに加えた変更を適用します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Document 内の指定されたボックスのサイズを返します。 |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | 指定されたページの回転を返します。 |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | ページ総数を返します。 |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | 指定されたページのページサイズを返します。 |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | 原点を (0, 0) から指定された点へ移動します。原点は左下で、単位はポイントです（1 インチ = 72 ポイント）。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | 変更された Document をストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | 変更された Document をファイルに保存します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | 垂直ブラインド |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | 垂直ブラインド |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | 下から上へのワイプ |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | 対角グリッター |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | 古いページが溶解します |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | 内向きボックス |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | 左右グリッター |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | 左右ワイプ |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | 外向きボックス |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | 右左ワイプ |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | IN 水平分割 |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | アウト水平分割 |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | イン垂直分割 |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | アウト垂直分割 |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | 上下グリッター |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | 上下ワイプ |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


