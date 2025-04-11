---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions クラス。レンダリングオプションを表します
type: docs
weight: 9760
url: /ja/net/aspose.pdf/renderingoptions/
---
## RenderingOptions クラス

レンダリングオプションを表します。

```csharp
public sealed class RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは次の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、!:FontRepository.Sources を介して追加されたフォントを検索します。3. テキストを分析して、そのアルファベットまたはスクリプトを特定し、それに応じてフォント名を提案します。これらのフォントをシステムから見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できるフォントをシステム内で検索します。 |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | バーコード最適化モードを取得または設定します。 |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | すべてのフォントが TTF Unicode バージョンに変換されることを示します。これは互換性の理由やフォントの使用を最適化するために便利です。新しい TTF フォントは、ソースフォントのすべてのシンボルを持つのではなく、テキストで使用されるシンボルのみを持ちます。 |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 欠落しているフォントの代わりに使用されるデフォルトのフォント名を取得または設定します。 |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | AppendRectangle 演算子の矩形の幅を増減させるために使用される値を取得または設定します。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | フォントの欠如に関連するエラーを無視するかどうかを示す値を取得または設定します。true - フォントの欠如に関するエラーが無視されることを意味します。無効なリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 補間の高品質モードを取得または設定します。 |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | フォントキャッシュ内のフォントの最大数。デフォルト値は 10 です。 |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | シンボルキャッシュ内のシンボルの最大数。デフォルト値は 100 です。 |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 次元最適化モードを取得または設定します。 |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | システムフォントがネイティブにレンダリングされるモードを取得または設定します。 |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | このフラグの使用はフォントヒンティングメカニズムをオンにします。フォントヒンティングは、アウトラインフォントの表示を調整するための数学的指示の使用です。このフラグをオンにすることで、テキストの可読性に関する問題が解決される場合があります。現在、このフラグの使用は、ソースドキュメントで使用されている TTF フォントにのみ効果があります。 |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | AppendRectangle 演算子の矩形の幅を増減させるために使用される値を取得または設定します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)