---
title: "クラス RedactionAnnotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.RedactionAnnotation クラス。Redact アノテーションを表します。"
type: docs
weight: 2490
url: /ja/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

Redact 注釈を表します。

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | RedactionAnnotation のコンストラクタ。Generator で使用するため。 |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | RedactAnnotation のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | アノテーションアクションの一覧を取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | アノテーションの境界特性を取得または設定します。[`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | 赤字が非アクティブなときに描画される境界線の色を取得または設定します。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | アノテーションが作成された日時を取得します。 |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | テキストの書式設定に使用されるデフォルトの外観文字列を取得または設定します。 |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | アノテーションを塗りつぶす色を取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | OverlayText のフォントサイズを取得または設定します。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | このアノテーションが「返信先」となるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 上の Annotation 名を取得または設定します。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | アノテーションの描画に使用される一定の不透明度値を取得または設定します。 |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | 赤字アノテーションに印刷するテキストを取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | アノテーションが含まれるページのインデックスを取得します。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。 |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | 削除対象となるコンテンツ領域の座標を指定する 8xN の数値配列です。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | アノテーションの矩形を取得または設定します。 |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | true の場合、オーバーレイテキストがアノテーション上に繰り返し表示されます。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | このアノテーションと InReplyTo で指定されたアノテーションとの関係（「返信タイプ」）を指定する文字列です。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation の外観辞書を取得します。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | オブジェクトの説明を表すテキストを取得します。 |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Overlay Text の配置を取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation のテキスト配置を取得または設定します。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 開いてアクティブな状態のアノテーションのポップアップウィンドウのタイトルバーに表示されるテキストラベルを取得または設定します。このエントリはアノテーションを追加したユーザーを識別します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | アノテーションを処理するためのビジタオブジェクトを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 行列変換に従ってパラメータと外観を更新します。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | アノテーションの状態と状態モデルをクリアします。例えば、アノテーションのレビュー状態をクリアします。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッドです。常に null を返します。 |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | アノテーションをフラット化します。つまり、アノテーションを削除し、その… |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮した注釈の矩形を返します。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | アノテーションの状態を取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | アノテーションの状態モデルを取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | アノテーションをフラット化し、ページ内容を赤字化します（つまり、赤字アノテーションの下のテキストと画像を削除します）。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | アノテーションの Marked および Unmarked 状態を設定します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。状態は対象アノテーションを作成したユーザーによって設定され、値は対象アノテーションの Title プロパティから取得されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |

### 関連項目

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


