---
title: "クラス CommonFigureAnnotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.CommonFigureAnnotation クラス。共通図形アノテーションを表す抽象クラスです。"
type: docs
weight: 1710
url: /ja/net/aspose.pdf.annotations/commonfigureannotation/
---
## CommonFigureAnnotation class

共通の図形注釈を表す抽象クラスです。

```csharp
public abstract class CommonFigureAnnotation : MarkupAnnotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CommonFigureAnnotation](commonfigureannotation/)(Document) | Generator で使用するためのコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | アノテーションアクションの一覧を取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | アノテーションの境界特性を取得または設定します。[`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | アノテーションが作成された日時を取得します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [Frame](../../aspose.pdf.annotations/commonfigureannotation/frame/) { get; set; } | アノテーションの Rect エントリと基になる正方形または円の実際の境界との数値的差異を示す矩形。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | このアノテーションが「返信先」となるアノテーションへの参照です。両方のアノテーションは文書の同じページにある必要があります。 |
| [InteriorColor](../../aspose.pdf.annotations/commonfigureannotation/interiorcolor/) { get; set; } | アノテーションの矩形または楕円を塗りつぶす内部色。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 上の Annotation 名を取得または設定します。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | アノテーションの描画に使用される一定の不透明度値を取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | アノテーションが含まれるページのインデックスを取得します。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | このアノテーションに関連付けられたテキストを入力または編集するためのポップアップアノテーションです。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | アノテーションの矩形を取得または設定します。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | このアノテーションと InReplyTo で指定されたアノテーションとの関係（「返信タイプ」）を指定する文字列です。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | アノテーションが開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation の外観辞書を取得します。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | オブジェクトの説明を表すテキストを取得します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation のテキスト配置を取得または設定します。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 開いてアクティブな状態のアノテーションのポップアップウィンドウのタイトルバーに表示されるテキストラベルを取得または設定します。このエントリはアノテーションを追加したユーザーを識別します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | アノテーション処理のためにビジターを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 行列変換に従ってパラメータと外観を更新します。 |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | アノテーションの状態と状態モデルをクリアします。例えば、アノテーションのレビュー状態をクリアします。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッドです。常に null を返します。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | アノテーションの内容をページに直接配置し、アノテーションオブジェクトは削除されます。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮した注釈の矩形を返します。 |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | アノテーションの状態を取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | アノテーションの状態モデルを取得します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | アノテーションの Marked および Unmarked 状態を設定します。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。状態は対象アノテーションを作成したユーザーによって設定され、値は対象アノテーションの Title プロパティから取得されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | アノテーションのレビュー状態を設定します。Marked と Unmarked の状態は Review StateModel に属さないため無視されます。注：state と statemodel キーを持つ他のテキストアノテーションに保存されている状態です。 |

### 関連項目

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


