---
title: "クラス MovieAnnotation"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.MovieAnnotation クラス。アニメーション画像と音声を含む映画アノテーションを表し、コンピュータ画面とスピーカーを通じて表示されます。アノテーションがアクティブになると映画が再生されます。"
type: docs
weight: 2200
url: /ja/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

コンピュータ画面とスピーカーを通じて表示されるアニメーション画像と音声を含むムービーannotationを表します。annotationがアクティブになると、ムービーが再生されます。

```csharp
public sealed class MovieAnnotation : Annotation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Generator と共に使用するためのコンストラクタです。 |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | 指定されたページに新しいサウンドアノテーションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | アノテーションアクションの一覧を取得します。 |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | 映画のバウンディングボックスの幅と高さをピクセル単位で取得または設定します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | アノテーションの境界特性を取得または設定します。[`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | 自己記述型映画ファイルを識別するファイル仕様を取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 上の Annotation 名を取得または設定します。 |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | アノテーションが含まれるページのインデックスを取得します。 |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | 映画を表すポスター画像を表示するかどうか、またその方法を指定するフラグまたはストリームを取得または設定します。true の場合、ポスター画像は映画ファイルから取得されます。false の場合、ポスターは表示されません。 |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | アノテーションの矩形を取得または設定します。 |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | 映画がページに対して時計回りに回転する角度（度）を取得または設定します。値は 90 の倍数でなければなりません。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation の外観辞書を取得します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation のテキスト配置を取得または設定します。 |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | 映画アノテーションのタイトルを取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | アノテーションを処理するためのビジタオブジェクトを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 行列変換に従ってパラメータと外観を更新します。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッドです。常に null を返します。 |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | アノテーションの内容をページに直接配置し、アノテーションオブジェクトは削除されます。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮した注釈の矩形を返します。 |

### 関連項目

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


