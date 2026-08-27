---
title: "クラス SvgSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.SvgSaveOptions クラス。SVG 形式へのエクスポート用の保存オプションです。"
type: docs
weight: 10410
url: /ja/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

SVG 形式へのエクスポート用保存オプションです。

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 出力を単一の zip アーカイブとして作成するかどうかを指定します。マルチページ ソース ドキュメントのページごとの svg ファイルの命名規則については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。この規則は zip 圧縮された出力ファイルセットにも適用されます。 |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | このフィールドには、変換中に作成された参照外部画像ファイル（埋め込み BMP や JPEG など）をカスタマイズして処理するために使用すべき保存戦略（存在する場合）を含めることができます。その戦略はリソースを処理し、生成された SVG 内で保存されたリソースの望ましい URI を表す文字列を返す必要があります。何らかの理由でこのファイルまたはそのファイルの処理をカスタムコードではなくコンバータ自身のコードで行う必要がある場合は、カスタムコードで 'imageSavingInfo' パラメータの変数のフラグ 'CustomProcessingCancelled' を設定してください。これは、外部のカスタムコードがないかのように、リソースの処理に必要なすべての手順をコンバータ自身が実行することをコンバータに通知します。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 出力ドキュメントを組版ポイントからピクセルにスケーリングするかどうかを指定します。 |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | このオプションは、要求された出力ファイル自体ではなく、同名のターゲットディレクトリ（まだ存在しない場合）を作成するかどうかを定義します。その場合、ディレクトリにはページごとのすべての出力 SVG 画像が格納されます（以下参照）。「いいえ」の場合、最初のページ以外のページの出力ファイルはメインの出力ファイルと同じディレクトリに作成されますが、ファイル名に _[2...n] のサフィックスが付加され、ページ番号で決まります。例えば、出力ファイルを "C:\\AsposeTests\\output.svg" と定義し、複数のページの svg ファイルが出力される場合、ページのファイルはディレクトリ "C:\\AsposeTests\\" にも作成され、'output.svg', 'output_2.svg', 'output_3.svg' などの名前になります。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

## 例

次の例は、PDF ファイルを SVG ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF ファイルへのパスです。
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// 出力 SVG ファイルへのパス。
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// SvgSaveOptions を初期化	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// SVG ファイルを保存
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


