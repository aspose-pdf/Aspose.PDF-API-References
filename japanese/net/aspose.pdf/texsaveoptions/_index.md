---
title: Class TeXSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXSaveOptions クラス。TeX 形式へのエクスポートのための保存オプション
type: docs
weight: 10400
url: /ja/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions クラス

TeX 形式へのエクスポートのための保存オプション

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントのグリフが aps ページを準備する際にキャッシュされるかどうかを示すブール値を取得または設定します。PDFを他の形式に変換する際のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | _outDirectoryPath パラメータのプロパティ。 |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | 変換後のページ数を返します。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションであり、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合は保存操作を中止する必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | フォントエンコーディングリストにフォントエンコーディングを追加します |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | フォントエンコーディングリストをクリアします |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイルの背景画像から構成された背景画像（ページまたはテーブルセルの）があります。この場合、ターゲット形式のレンダラー（例：DOCS形式のMsWord）は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング（アンチエイリアス）の技術が Acrobat Reader とは異なるためです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

## 例

次の例は、PDF ファイルを TeX ファイルに変換する方法を示しています

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// The path to output TeX File.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// Save TeX file
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)