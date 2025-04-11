---
title: Class MarkupAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MarkupAnnotation クラス。マークアップ注釈を表す抽象クラス
type: docs
weight: 2020
url: /ja/net/aspose.pdf.annotations/markupannotation/
---
## MarkupAnnotation クラス

マークアップ注釈を表す抽象クラス。

```csharp
public abstract class MarkupAnnotation : Annotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkupAnnotation](markupannotation/)(Document) | マークアップ注釈のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 注釈アクションのリストを取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界特性を取得または設定します。 [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 注釈が作成された日時を取得します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDFジェネレーター用）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | この注釈が「返信先」とする注釈への参照。両方の注釈はドキュメントの同じページに存在する必要があります。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示すブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制するブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します（PDF生成用） |
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
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z-オーダーを示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | 注釈処理のためのビジターを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | マトリックス変換に従ってパラメータと外観を更新します。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 注釈の状態と状態モデルをクリアします。たとえば、注釈のレビュー状態をクリアします。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッド。常に null を返します。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 注釈の内容をページに直接配置し、注釈オブジェクトを削除します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮して注釈の矩形を返します。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 注釈の状態を取得します。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 注釈の状態モデルを取得します。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 注釈のマークされた状態とマークされていない状態を設定します。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/#setreviewstate)(AnnotationState) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。状態は、ターゲット注釈を作成したユーザーによって設定されます。値はターゲット注釈の Title プロパティから取得されます。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/#setreviewstate_1)(AnnotationState, string) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。状態は、状態と statemodel キーを持つ他のテキスト注釈に保存されます。 |

### 参照

* クラス [Annotation](../annotation/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)