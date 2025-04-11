---
title: Class EpubSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptions クラス。EPUB 形式へのエクスポートのための保存オプション
type: docs
weight: 4060
url: /ja/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions クラス

EPUB 形式へのエクスポートのための保存オプション

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントのグリフが APS ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDF から他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | EPUB ドキュメントのタイトルを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションであり、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | PDF ファイル（通常は固定レイアウトを持つ）が変換されるとき、変換エンジンは元のドキュメントの著者の意図を復元し、フローレイアウトで結果を生成するためにグループ化と多層分析を試みます。このプロパティは、コンテンツの認識のための望ましい方法に合わせてその変換を調整します。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイル背景画像から構成される背景画像（ページまたはテーブルセルの）があります。この場合、ターゲット形式のレンダラー（例：DOCS 形式の MsWord）は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング（アンチエイリアス）の技術が Acrobat Reader とは異なるためです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用してその不要な効果を取り除いてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

## 例

次の例は、PDF ファイルを EPUB ファイルに変換する方法を示しています

```csharp
	[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// The path to output EPUB File.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Initialize EpubSaveOptions 	
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Save EPUB file
		pdfDocument.Save(epubFile, saveOptions);
	}
````

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)