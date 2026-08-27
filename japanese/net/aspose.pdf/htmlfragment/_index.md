---
title: "クラス HtmlFragment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlFragment クラス。HTML フラグメントを表します。"
type: docs
weight: 5650
url: /ja/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

HTML フラグメントを表します。

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | HtmlFragment クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | このクラスのインスタンスに HTML を読み込み（およびレンダリング）するために使用される HtmlLoadOptions を取得または設定します。特定のインスタンスの HTML インポートに特定の設定が必要な場合に使用してください（例: そのインスタンスがインポートされた HTML の特定の BasePath を使用する必要がある場合や、外部リソースの特定のローダーを使用する必要がある場合）。パラメータがデフォルト（null）の場合、標準の HTML 読み込みオプションが使用されます。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | 単語の改行を取得または設定します。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | 段落がデフォルトの余白を持つかどうかを取得または設定します。余白がない場合は 0 になります。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | HtmlFragment の矩形を取得します。 |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | フォントを取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | HTML フラグメントを複製します。 |

### 関連項目

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


