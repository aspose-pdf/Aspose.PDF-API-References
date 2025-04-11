---
title: Class LineAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.LineAnnotation クラス。ライン注釈を表すクラス
type: docs
weight: 1980
url: /ja/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation クラス

ライン注釈を表すクラス。

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [LineAnnotation](lineannotation/#constructor)(Document, Point, Point) | Generator と共に使用するためのコンストラクタ。 |
| [LineAnnotation](lineannotation/#constructor_1)(Page, Rectangle, Point, Point) | 指定されたページに新しいライン注釈を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 注釈アクションのリストを取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界特性を取得または設定します。 [`Border`](../annotation/border/) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset/) { get; set; } | 通常の位置からのキャプションテキストのオフセットを取得または設定します。 |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition/) { get; set; } | 注釈キャプションの位置を取得または設定します。 |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 注釈が作成された日時を取得します。 |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending/) { get; set; } | ラインの終了点を取得または設定します。 |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle/) { get; set; } | ラインの終了点のスタイルを取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDFジェネレーター用）。 |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | この注釈が「返信先」とする注釈への参照。両方の注釈はドキュメントの同じページに存在する必要があります。 |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent/) { get; set; } | ライン注釈の意図を取得または設定します。 |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor/) { get; set; } | 注釈の内部色を取得または設定します。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示すブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制するブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline/) { get; set; } | リーダーラインの長さを取得または設定します。 |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension/) { get; set; } | リーダーラインの延長の長さを取得または設定します。 |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset/) { get; set; } | リーダーラインのオフセットを取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側のマージンを取得または設定します（PDF生成用） |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure/) { get; set; } | この注釈に指定された測定単位。 |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 注釈が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | ページ上の注釈名を取得または設定します。 |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 注釈を描画する際に使用される不透明度の定数値を取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 注釈を含むページのインデックスを取得します。 |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | この注釈に関連するテキストを入力または編集するためのポップアップ注釈。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 注釈の矩形を取得または設定します。 |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | この注釈と InReplyTo で指定された注釈との関係（「返信タイプ」）を指定する文字列。 |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 注釈が開かれたときにポップアップウィンドウに表示されるリッチテキスト文字列を取得または設定します。 |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption/) { get; set; } | コンテンツがキャプションとして表示されるかどうかを決定するブールフラグを取得または設定します。 |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting/) { get; set; } | ラインの開始点を取得または設定します。 |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle/) { get; set; } | ラインの開始点のスタイルを取得または設定します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 注釈の外観辞書を取得します。 |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | オブジェクトの説明を表すテキストを取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 注釈のテキストの配置を取得または設定します。 |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 注釈のタイトルバーに表示されるテキストを取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは、ZIndex が小さいグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept/)(AnnotationSelector) | 注釈処理のためにビジターを受け入れます。 |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize/)(Matrix) | マトリックス変換に従って開始点と終了点を更新します。 |
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