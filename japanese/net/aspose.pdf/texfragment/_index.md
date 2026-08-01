---
title: "クラス TeXFragment"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.TeXFragment クラス。TeX フラグメントを表します"
type: docs
weight: 10540
url: /ja/net/aspose.pdf/texfragment/
---
## TeXFragment class

TeX フラグメントを表します。

```csharp
public class TeXFragment : FormattedFragment
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | HtmlFragment クラスの新しいインスタンスを初期化します。 |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | HtmlFragment クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | このクラスのインスタンスに LaTeX をロード（およびレンダリング）するために使用される TeXLoadOptions を取得または設定します。特定のインスタンスに対して LaTeX のインポート設定を個別に使用する必要がある場合に使用してください（例：このインスタンスまたはそのインスタンスがインポートされた LaTeX の特定の BasePath を使用する必要がある場合や、外部リソースの特定のローダーを使用する必要がある場合）。パラメータがデフォルト（null）の場合、標準の LaTeX ロードオプションが使用されます。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | フラグメントをクローンします。 |

### 関連項目

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


