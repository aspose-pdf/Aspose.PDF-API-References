---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions クラス。マークダウン形式でのドキュメント保存オプションクラスを表します。
type: docs
weight: 6910
url: /ja/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions クラス

マークダウン形式でのドキュメント保存オプションクラスを表します。

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | コンテンツをマークダウンに抽出するための矩形領域を取得または設定します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフが APS ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 生成されたドキュメントの強調スタイルを取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | ベクターグラフィックスを抽出するかどうかを示すプロパティを取得または設定します。 |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | フォントサイズ認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティの値が設定されている場合、ヘッダー認識 !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic 戦略が選択されます。ドキュメントにブックマークが含まれていても、!:PdfToMarkdown.HeadingRecognitionStrategy.Auto 戦略が設定されます。 |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 見出し認識戦略を取得または設定します。 |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 生成されたドキュメントの見出しスタイルを取得または設定します。 |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 生成されたドキュメントの改行スタイルを取得または設定します。 |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 画像などのドキュメントリソースを保存するためのディレクトリ名を取得または設定します。値が指定されていない場合、画像はマークダウンファイル自体と同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは、保存されたマークダウンファイルのディレクトリに自動的に作成されます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 下付き文字と上付き文字を変換する許可を取得または設定します。この値はデフォルトで true です。 |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | テキストの左側と右側に画像を挿入するために img タグを使用する許可を取得または設定します。この場合、マークダウンビューワーでは、テキストが画像の周りに折り返されます。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合、保存操作は停止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイル背景画像から構成された背景画像（ページまたはテーブルセルの）があります。この場合、ターゲット形式のレンダラー（例：DOCS形式の MsWord）は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング（アンチエイリアス）の技術が Acrobat Reader とは異なるためです。このような目に見える境界が同じ背景画像の部分間に存在するように見える場合は、この設定を使用してその不要な効果を取り除いてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)