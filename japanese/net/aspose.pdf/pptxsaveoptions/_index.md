---
title: Class PptxSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PptxSaveOptions クラス。SVG 形式へのエクスポートのための保存オプション
type: docs
weight: 9480
url: /ja/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions クラス

SVG 形式へのエクスポートのための保存オプション

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントのグリフが APS ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDF から他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | このハンドラは、変換進行状況イベントを処理するために使用できます。例えば、進行状況バーや処理されたページの現在の量に関するメッセージを表示するために使用できます。進行状況をコンソールに表示するハンドラのコードの例は次のとおりです： |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | 画像の解像度 (dpi) を取得または設定します。デフォルトは 192 dpi です。 |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | テキスト列の認識を切り替えます |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | true に設定すると、画像が他のすべてのグラフィックから分離されます |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | true に設定すると、すべてのコンテンツが画像として認識されます (ページごとに 1 つ) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイル背景画像から構成されたページまたはテーブルセルの背景画像が含まれています。この場合、ターゲット形式のレンダラー (例えば、DOCS 形式の MsWord) は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング (アンチエイリアス) の技術が Acrobat Reader とは異なるためです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用してその不要な効果を取り除いてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

## 例

次の例は、PDF ファイルを PPT または PPTX ファイルに変換する方法を示しています

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// The path to your PPT or PPTX File.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Save PPT or PPTX file
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)