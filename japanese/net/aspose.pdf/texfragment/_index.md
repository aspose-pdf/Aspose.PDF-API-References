---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXFragment クラス。TeX フラグメントを表します
type: docs
weight: 10360
url: /ja/net/aspose.pdf/texfragment/
---
## TeXFragment クラス

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平方向の配置を取得または設定します |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントのハイパーリンクを取得または設定します（PDF ジェネレーター用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します（PDF 生成用） |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | このクラスのインスタンスに LaTeX を読み込む（およびレンダリングする）ために使用される TeXLoadOptions を取得または設定します。特定のインスタンスの LaTeX インポートに特定の設定を使用する必要がある場合に使用してください（例えば、このインスタンスがインポートされた LaTeX の特定の BasePath を使用する必要がある場合や、外部リソースの特定のローダーを使用する必要がある場合）。パラメータがデフォルト（null）の場合、標準の LaTeX 読み込みオプションが使用されます。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直方向の配置を取得または設定します |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは、ZIndex が小さいグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | フラグメントをクローンします。 |

### 参照

* クラス [FormattedFragment](../formattedfragment/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)