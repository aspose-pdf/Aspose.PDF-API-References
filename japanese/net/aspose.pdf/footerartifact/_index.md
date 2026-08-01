---
title: "クラス FooterArtifact"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.FooterArtifact クラス。フッターアーティファクトを説明します。ページのフッターを設定するために使用できる場合があります。"
type: docs
weight: 5050
url: /ja/net/aspose.pdf/footerartifact/
---
## FooterArtifact class

フッターアーティファクトを記述します。ページのフッターを設定するために使用できます。

```csharp
public class FooterArtifact : Artifact
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FooterArtifact](footerartifact/)() | Footer Artifact のインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | アーティファクトの水平配置。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | アーティファクトの垂直配置。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | アーティファクトの下余白。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | アーティファクトの内部オペレーターのコレクションを取得します。 |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | アーティファクトのサブタイプ名を取得します。サブタイプが標準でない場合に使用できます。 |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | アーティファクトのタイプ名を取得します。タイプが標準でない場合に使用できます。 |
| [Form](../../aspose.pdf/artifact/form/) { get; } | アーティファクトの XForm を取得します（XForm が使用されている場合）。 |
| [Image](../../aspose.pdf/artifact/image/) { get; } | アーティファクトの画像を取得します（存在する場合）。 |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | true の場合、アーティファクトはページ内容の背後に配置されます。 |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | アーティファクトの左余白。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | 複数行テキストアーティファクトの行。 |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | アーティファクトの不透明度を取得または設定します。可能な値は 0..1 の範囲です。 |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | アーティファクトの位置を取得または設定します。このプロパティが指定されている場合、余白と配置は無視されます。 |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | アーティファクトの矩形を取得します。 |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | アーティファクトの右余白。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | アーティファクトの回転角度を取得または設定します。 |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | アーティファクトのサブタイプを取得します。アーティファクトに標準外のサブタイプがある場合、CustomSubtype を通じてサブタイプ名を取得できます。 |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | アーティファクトのテキストを取得します。 |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | アーティファクトテキストのテキスト状態。 |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | アーティファクトの上余白。位置が Position プロパティで明示的に指定されている場合、この値は無視されます。 |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | アーティファクトのタイプを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 遅延更新を開始します。同じアーティファクトに対して複数の変更を行う必要がある場合に、パフォーマンス向上のためにこの機能を使用します。通常、アーティファクトのプロパティが変更されるたびにアーティファクト演算子が変更されます。これにより、アーティファクトが変更されるたびにページの内容が変更されます。この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置します。これにより、ページの内容を一度だけ変更できます。 |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | アーティファクトを破棄します。 |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | アーティファクトのカスタム値を取得します。 |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | アーティファクトからカスタム値を削除します。 |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() 呼び出し後に行われたアーティファクト内のすべての更新を保存します。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | アーティファクトの画像を設定します。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | アーティファクトの画像を設定します。 |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | アーティファクトのテキストとテキストプロパティを設定します。複数行を指定できます。 |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | ページ番号と置き換えられる文字列を設定します。デフォルト値は # です。 |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | PDF ページを設定します。このページは document ページ上にアーティファクトとして配置されます。 |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | アーティファクトのテキストを設定します。 |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | アーティファクトのテキストとテキストプロパティを設定します。 |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | アーティファクトのカスタム値を設定します。 |

### 関連項目

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


