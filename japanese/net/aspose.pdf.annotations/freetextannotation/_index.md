---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FreeTextAnnotation クラス。ページ上に直接テキストを表示する自由テキスト注釈を表します。通常のテキスト注釈とは異なり、自由テキスト注釈には開いている状態や閉じている状態がなく、ポップアップウィンドウに表示されるのではなく、テキストは常に表示されます。
type: docs
weight: 1810
url: /ja/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation クラス

ページ上に直接テキストを表示する自由テキスト注釈を表します。通常のテキスト注釈とは異なり、自由テキスト注釈には開いている状態や閉じている状態がなく、ポップアップウィンドウに表示されるのではなく、テキストは常に表示されます。

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Generator と共に使用するためのコンストラクタ。 |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | 指定されたページに新しい自由テキスト注釈を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 注釈アクションのリストを取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | 注釈の種類を取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界特性を取得または設定します。 [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | コールアウトラインを指定するポイントの配列。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 注釈が作成された日時を取得します。 |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | テキストのフォーマットに使用されるデフォルトの外観文字列を取得または設定します。 |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | FreeText 注釈のデフォルトの外観を表すオブジェクト。 |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | デフォルトスタイル文字列を取得または設定します。 |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | 行の終了点のための行の終了スタイルを取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレーター用）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | この注釈が「返信先」とする注釈への参照。両方の注釈はドキュメントの同じページに存在する必要があります。 |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | 自由テキスト注釈の意図を取得または設定します。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | 注釈のテキストを表示する際に使用されるクワディング（整列）の形式を指定するコードを取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します（PDF 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 注釈が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | ページ上の注釈名を取得または設定します。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 注釈を描画する際に使用される不透明度の定数値を取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 注釈を含むページのインデックスを取得します。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | この注釈に関連付けられたテキストを入力または編集するためのポップアップ注釈。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 注釈の矩形を取得または設定します。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | この注釈と InReplyTo で指定された注釈との関係（「返信タイプ」）を指定する文字列。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 注釈が開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | 注釈の回転角度。 |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | 行の終了点のための行の終了スタイルを取得または設定します。このプロパティは廃止予定です。EndingStyle を使用してください。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 注釈の外観辞書を取得します。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | オブジェクトの説明を表すテキストを取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 注釈のテキストの整列を取得または設定します。 |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | 2つの矩形の間の数値的な違いを説明する矩形：注釈の Rect エントリと、その矩形内に含まれる矩形。内部の矩形は注釈のテキストが表示される場所です。 |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | 外観のテキストのスタイルを取得または設定します。テキストスタイルが変更されると、テキストの外観が更新されます。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 注釈のタイトルバーに表示されるテキストを取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直整列を取得または設定します。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。大きな ZIndex を持つグラフは、小さな ZIndex を持つグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | 注釈を処理するためにビジターオブジェクトを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | マトリックス変換に従ってパラメータと外観を更新します。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 注釈の状態と状態モデルをクリアします。たとえば、注釈のレビュー状態をクリアします。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッド。常に null を返します。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 注釈の内容をページに直接配置し、注釈オブジェクトを削除します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮して注釈の矩形を返します。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 注釈の状態を取得します。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 注釈の状態モデルを取得します。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 注釈のマークされた状態とマークされていない状態を設定します。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。状態は、ターゲット注釈を作成したユーザーによって設定されます。値は、ターゲット注釈の Title プロパティから取得されます。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 注釈のレビュー状態を設定します。マークされた状態とマークされていない状態は、レビュー状態モデルに属さないため無視されます。状態は、状態および statemodel キーを持つ他のテキスト注釈に保存されます。 |

### 参照

* クラス [MarkupAnnotation](../markupannotation/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)