---
title: "RenderingOptions クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.RenderingOptions クラス。レンダリングオプションを表します。"
type: docs
weight: 9910
url: /ja/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

レンダリングオプションを表します。

```csharp
public sealed class RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | 必要に応じてフォントを置き換え、テキスト内のすべての文字が表示できるようにします。フォント置換アルゴリズムは以下の手順で実行されます：1. ユーザーが DefaultFontName プロパティを明示的に設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義フォントが設定されていない場合、!:FontRepository.Sources で追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステムで検索します。 |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | バーコード最適化モードを取得または設定します。 |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | すべてのフォントが TTF Unicode バージョンに変換されることを示します。これは互換性の観点やフォント使用量の最適化に有用です。新しい TTF フォントは元のフォントのすべてのシンボルを含むのではなく、テキストで使用されているシンボルだけを含みます。 |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 欠落フォントの代替に使用されるフォントの既定名を取得または設定します。 |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | フォントが存在しないことに関連するエラーを無視するかどうかの指示を取得または設定します。true の場合、フォントが存在しないエラーは無視されます。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。デフォルトは false です。 |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 補間の高品質モードを取得または設定します。 |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | フォントキャッシュ内のフォント最大数。既定値は 10 です。 |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | シンボルキャッシュ内のシンボル最大数。既定値は 100 です。 |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 次元最適化モードを取得または設定します。 |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | システムフォントがネイティブにレンダリングされるモードを取得または設定します。 |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | このフラグの使用によりフォントヒンティング機構が有効になります。フォントヒンティングとは、アウトラインフォントの表示を調整するための数学的指示を使用することです。場合によっては、このフラグをオンにすることでテキストの可読性に関する問題が解決することがあります。現在のところ、このフラグの使用はTTFフォントに対してのみ効果があり、これらのフォントがソースドキュメントで使用されている場合に限られます。 |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | AppendRectangle 演算子の矩形幅を増減させるために使用される値を取得または設定します。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


