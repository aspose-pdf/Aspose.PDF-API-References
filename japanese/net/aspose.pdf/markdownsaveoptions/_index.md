---
title: "MarkdownSaveOptions クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.MarkdownSaveOptions クラス。markdown 形式での Document 保存オプションクラスを表します。"
type: docs
weight: 7050
url: /ja/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown 形式でのドキュメント保存オプションクラスを表します。

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | markdown にコンテンツを抽出するための矩形領域を取得または設定します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 生成された Document の強調スタイルを取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | ベクトル グラフィックを抽出すべきかを示すプロパティを取得および設定します。 |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | FontSize 認識ヘッダー戦略で使用する期待される見出しレベルを定義します。このプロパティ値が設定されている場合、ドキュメントにブックマークが含まれていても、ヘッダー認識ヒューリスティック戦略が !:PdfToMarkdown.HeadingRecognitionStrategy.Auto 戦略が設定されたときに選択されます。 |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 見出し認識戦略を取得または設定します。 |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 生成されたドキュメントの見出しスタイルを取得または設定します。 |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 生成されたドキュメントの改行スタイルを取得または設定します。 |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 画像などのドキュメントリソースを保存するディレクトリ名を取得および設定します。値が指定されていない場合、画像は markdown ファイル自体と同じディレクトリに書き込まれます。これはパスではなく、名前だけです！このディレクトリは保存された markdown ファイルのディレクトリ内に自動的に作成されます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 下付き文字と上付き文字への変換許可を取得および設定します。この値はデフォルトで true です。 |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | テキストの左側および右側に画像を挿入するための img タグの使用許可を取得および設定します。この場合、markdown ビューアではテキストが画像の周りに折り返されます。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


