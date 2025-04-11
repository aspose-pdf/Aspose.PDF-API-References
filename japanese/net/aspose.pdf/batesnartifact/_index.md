---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BatesNArtifact クラス。クラスは Bates 番号付けアーティファクトを説明します
type: docs
weight: 2850
url: /ja/net/aspose.pdf/batesnartifact/
---
## BatesNArtifact クラス

クラスは Bates 番号付けアーティファクトを説明します。

```csharp
public class BatesNArtifact : PaginationArtifact
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | `BatesNArtifact` クラスの新しいインスタンスを初期化します。このコンストラクタは内部的で、デフォルト値を持つヘッダーアーティファクトインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | アーティファクトの水平方向の配置。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | アーティファクトの垂直方向の配置。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | アーティファクトの下余白。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | アーティファクト内部オペレーターのコレクションを取得します。 |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | アーティファクトのサブタイプの名前を取得します。アーティファクトのサブタイプが標準サブタイプでない場合に使用されることがあります。 |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | アーティファクトのタイプの名前を取得します。アーティファクトのタイプが非標準の場合に使用されることがあります。 |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | アーティファクトの終了ページ番号を取得または設定します。値は 0 以上でなければなりません。0 未満の値が設定された場合は、0 に調整されます。デフォルト値の 0 は、終了ページの境界がないことを意味します。 |
| [Form](../../aspose.pdf/artifact/form/) { get; } | アーティファクトの XForm を取得します（XForm が使用されている場合）。 |
| [Image](../../aspose.pdf/artifact/image/) { get; } | アーティファクトの画像を取得します（存在する場合）。 |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | true の場合、アーティファクトはページの内容の後ろに配置されます。 |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | アーティファクトの左余白。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | マルチラインテキストアーティファクトの行。 |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | Bates 番号付けの桁数を取得または設定します。値は 3 から 15 の間でなければなりません（両端を含む）。3 未満の値が設定された場合は、3 に調整されます。15 を超える値が設定された場合は、15 に調整されます。デフォルト値は 6 です。 |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | アーティファクトの不透明度を取得または設定します。可能な値は 0..1 の範囲です。 |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | アーティファクトの位置を取得または設定します。このプロパティが指定されている場合、余白と配置は無視されます。 |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | Bates 番号に追加されるプレフィックスを取得または設定します。 |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | アーティファクトの矩形を取得します。 |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | アーティファクトの右余白。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | アーティファクトの回転角度を取得または設定します。 |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | Bates 番号付けの開始番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は、1 に調整されます。 |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | アーティファクトの開始ページ番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は、1 に調整されます。 |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | アーティファクトが適用されるページのサブセットを取得または設定します（例：すべてのページ、偶数ページ、奇数ページ）。 |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | アーティファクトのサブタイプを取得します。アーティファクトが非標準のサブタイプを持つ場合、サブタイプの名前は CustomSubtype を介して読み取ることができます。 |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | Bates 番号に追加されるサフィックスを取得または設定します。 |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | アーティファクトのテキストを取得または設定します。 |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | アーティファクトテキストのテキスト状態。 |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | アーティファクトの上余白。位置が明示的に指定されている場合（Position プロパティで）、この値は無視されます。 |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | アーティファクトのタイプを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | 遅延更新を開始します。この機能は、同じアーティファクトに対して複数の変更を行う必要がある場合にパフォーマンスを向上させるために使用します。通常、アーティファクトのプロパティが変更されると、アーティファクトオペレーターは常に変更されます。これにより、アーティファクトが変更されるたびにページの内容が変更されます。この効果を避けるために、すべてのアーティファクトの更新を StartUpdates/SaveUpdates 呼び出しの間に置きます。これにより、ページの内容を一度だけ変更できます。 |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | アーティファクトを破棄します。 |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | アーティファクトのカスタム値を取得します。 |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | アーティファクトからカスタム値を削除します。 |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() 呼び出しの後に行われたアーティファクトのすべての更新を保存します。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | アーティファクトの画像を設定します。 |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | アーティファクトの画像を設定します。 |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | アーティファクトのテキストとテキストプロパティを設定します。複数行を指定できます。 |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | ページ番号で置き換えられる文字列を設定します。デフォルト値は # です。 |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | ドキュメントページにアーティファクトとして配置される PDF ページを設定します。 |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | アーティファクトのテキストを設定します。 |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | アーティファクトのテキストとテキストプロパティを設定します。 |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | アーティファクトのカスタム値を設定します。 |

### 参照

* クラス [PaginationArtifact](../paginationartifact/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)