---
title: "Class XpsSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XpsSaveOptions クラス。Xps 形式へのエクスポート用保存オプション"
type: docs
weight: 11710
url: /ja/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Xps 形式へのエクスポート用保存オプションです。

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | ソースと宛先のフォーマットペアに対してバッチ変換が適用可能な場合のバッチサイズを定義します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | デフォルトのフォント名を取得/設定します。埋め込みフォント名がシステムに見つからない場合に使用されます。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | 透過（OCR 処理済み）テキストを保持するかどうかを示します。 |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | 埋め込み TrueType フォントを使用するフラグを取得/設定します。埋め込み TrueType フォントの使用を回避すると、変換時間を短縮できます。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

## 例

次の例は、PDF ファイルを XPS ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF ファイルへのパス
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// XPS ファイルへのパス
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// XpsSaveOptions を初期化する	
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// XPS ファイルを保存する
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


