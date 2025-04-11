---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions クラス。SVG 形式へのエクスポートのための保存オプション
type: docs
weight: 10230
url: /ja/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions クラス

SVG 形式へのエクスポートのための保存オプション

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| Name | Description |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | 既定のコンストラクタ。 |

## プロパティ

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | ページを準備する際にフォントグリフがキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他のフォーマットへの変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後に Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つPDFドキュメントから画像またはテキストを抽出する機能を有効にします。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 保存データの形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandlerは、ContinueまたはAbortを指定するReturnAction列挙体の項目を返します。Continueがデフォルトの動作であり、保存操作は継続されますが、ユーザーがAbortを返す場合、保存操作は中断されます。 |

## フィールド

| Name | Description |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 出力が1つのzipアーカイブとして作成されるかどうかを指定します。複数ページのソースドキュメントのページのsvgファイルの命名規則については、'TreatTargetFileNameAsDirectory' オプションのコメントを参照してください。これらのルールは、zip化された出力ファイルセットにも適用されます。 |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | このフィールドには、保存済みSVGに埋め込まれた参照外部画像ファイル（例: 埋め込みBMPまたはJPEG）のカスタマイズされた処理のため、変換中に使用される保存戦略が含まれる場合があります。その戦略はリソースを処理し、生成されたSVG内の保存されたリソースの望ましいURIを表す文字列を返す必要があります。何らかの理由で特定のファイルの処理が外部のカスタムコードではなく、コンバータ自身のコードによって行われる必要がある場合は、カスタムコード内で 'imageSavingInfo' パラメーターの変数の 'CustomProcessingCancelled' フラグを設定してください。これは、そのリソースの処理に必要なすべての手順が、外部カスタムコードが存在しないかのように、コンバータ自身によって実行されるべきであることを示します。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | ページを複数のスレッドで処理します。 |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 出力ドキュメントをタイポグラフィックポイントからピクセルにスケーリングするかどうかを指定します。 |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | このオプションは、要求された出力ファイル自体の代わりに、要求された出力ファイルと同じ名前のターゲットディレクトリ（存在しない場合は作成）が作成されるかどうかを定義します。そうすると、そのディレクトリには、以下に記載されているように、すべてのページの出力SVGイメージが含まれます。そうでない場合、最初のページ以外の出力ファイルは、主要な出力ファイルと同じディレクトリに作成されますが、ページ番号によって定義された _[2...n] のファイル名の接尾辞が付加されます。例: 出力ファイルとして "C:\AsposeTests\output.svg" を定義し、複数のページのsvgファイルが出力される場合、各ページのファイルは "C:\AsposeTests\" ディレクトリにも作成され、'output.svg', 'output_2.svg', 'output_3.svg' などの名前が付けられます。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 場合によっては、PDFは複数の同じタイル状背景画像を並べて構成された背景画像（ページまたはテーブルセルの）を含むことがあります。その場合、ターゲットフォーマットのレンダラー（例: DOCS形式用のMsWord）は、画像のエッジスムージング（アンチエイリアス）の技法がAcrobat Readerと異なるため、背景画像のパーツ間に目に見える境界線を生成することがあります。エクスポートされたドキュメントに同じ背景画像のパーツ間に目に見える境界線が含まれているように見える場合は、この設定を使用してその不必要な効果を取り除いてみてください。注意！ この品質の最適化は通常、変換速度を大幅に低下させるため、本当に必要な場合にのみこのオプションを使用してください。 |

## 使用例

以下の例は、PDFファイルをSVGファイルに変換する方法を示しています.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
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

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)