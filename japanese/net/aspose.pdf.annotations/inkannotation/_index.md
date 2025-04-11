---
title: Class InkAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.InkAnnotation クラス。1つ以上の離散的なパスで構成されたフリーハンドの落書きを表します。
type: docs
weight: 1920
url: /ja/net/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation クラス

1つ以上の離散的なパスで構成されたフリーハンドの「落書きを」表します。

```csharp
public sealed class InkAnnotation : MarkupAnnotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [InkAnnotation](inkannotation/#constructor)(Document, IList&lt;Point[]&gt;) | Generator 用の Ink 注釈のコンストラクタ。 |
| [InkAnnotation](inkannotation/#constructor_1)(Page, Rectangle, IList&lt;Point[]&gt;) | 指定されたページに新しい Ink 注釈を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 注釈アクションのリストを取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/inkannotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界特性を取得または設定します。 [`Border`](../annotation/border/) |
| [CapStyle](../../aspose.pdf.annotations/inkannotation/capstyle/) { get; set; } | Ink 注釈の線の端のスタイル。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 注釈が作成された日時を取得します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレーター用）。 |
| [InkList](../../aspose.pdf.annotations/inkannotation/inklist/) { get; set; } | Point[] 配列で表される独立した線のジェスチャーのリストを取得または設定します。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | この注釈が「返信先」とする注釈への参照。両方の注釈はドキュメントの同じページに存在する必要があります。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します（PDF 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 注釈が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | ページ上の注釈名を取得または設定します。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 注釈を描画する際に使用される不透明度の定数値を取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 注釈を含むページのインデックスを取得します。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | この注釈に関連付けられたテキストを入力または編集するためのポップアップ注釈。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 注釈の矩形を取得または設定します。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | この注釈と InReplyTo で指定された注釈との関係（「返信タイプ」）を指定する文字列。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 注釈が開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 注釈の外観辞書を取得します。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | オブジェクトの説明を表すテキストを取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 注釈のテキストの配置を取得または設定します。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 注釈のタイトルバーに表示されるテキストを取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/inkannotation/accept/)(AnnotationSelector) | 注釈を処理するためにビジターオブジェクトを受け入れます。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/inkannotation/changeafterresize/)(Matrix) | マトリックス変換に従って InkList 内のポイントを更新します。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 注釈の状態と状態モデルをクリアします。たとえば、注釈のレビュー状態をクリアします。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッド。常に null を返します。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 注釈の内容をページに直接配置し、注釈オブジェクトを削除します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮して注釈の矩形を返します。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 注釈の状態を取得します。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 注釈の状態モデルを取得します。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 注釈のマークされた状態とマークされていない状態を設定します。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。状態は、ターゲット注釈を作成したユーザーによって設定されます。値はターゲット注釈の Title プロパティから取得されます。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。他のテキスト注釈に保存されている状態には、state および statemodel キーがあります。 |

### 参照

* クラス [MarkupAnnotation](../markupannotation/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)