---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions クラス。Doc 形式へのエクスポートのための保存オプション
type: docs
weight: 3750
url: /ja/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions クラス

Doc 形式へのエクスポートのための保存オプション

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | 段落または改行を使用 |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | バッチ変換がソースと宛先フォーマットのペアに適用可能な場合のバッチサイズを定義します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | APS ページを準備する際にフォントグリフがキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Type3 フォントの変換を取得または設定します。Type 3 フォントでは、グリフはグラフィックスオペレーターのストリームによって定義されます。これは、DOC/DOCX 出力でテキストの代わりに画像が表示されることを意味します。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルにテキストを取得します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを持つ PDF ドキュメントから画像またはテキストを抽出する機能をオンにします。 |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 出力形式 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 変換された画像の X 解像度。 |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 変換された画像の Y 解像度。 |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | このパラメータは、テキスト行を段落にグループ化するために使用されます。2つの相対的なテキスト行の間にどれだけの距離があるかを決定します。テキスト行の高さの百分率で指定されます。 |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | メモリ保存モードで変換する際に一時データを保持するためのパス（ファイル名またはディレクトリ名）を定義します。 |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 認識モード。 |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 箇条書きの認識をオンにします |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | PDF内の単語は、文字や音節を独立して印刷するオペレーターで表現されることがあります。したがって、単語を検出するためには、実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF での単語の認識中に単語間の距離として扱われるテキスト要素（文字、音節）間のスペースの幅を定義します。（この幅の少なくとも空白が文字の間に存在する場合、テキスト要素は異なる単語に属します）。フォントサイズに対して規定されています - 1.0 は想定される単語のフォントサイズの 100% を意味します。注意！これは、ソース PDF がフォントから最適値を計算できない特定のまれに使用されるフォントを含む場合にのみ使用されます。したがって、ほとんどのケースでは、このパラメータは結果のドキュメントに何も変更を加えません。 |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | フォントの再保存手順を取得または設定します。true に設定すると、すべてのページでフォントを再読み込みし、以前のフォントプロパティの影響を避け、新しく作成されたフォントを最初から読み込みます。パフォーマンスを向上させたい場合は、このオプションを false に設定します。デフォルト値は true です。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションであり、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合、保存操作は中止されるべきです。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | このハンドラーは、変換進行状況イベントを処理するために使用できます。例えば、進行状況バーや処理されたページの現在の量に関するメッセージを表示するために使用できます。進行状況をコンソールに表示するハンドラーのコードの例は次のとおりです： |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 複数のスレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 時々、PDF には、隣接する同じタイル背景画像から構成される背景画像（ページまたはテーブルセルの）が含まれています。この場合、ターゲットフォーマットのレンダラー（例えば、DOCS 形式の MsWord）は、背景画像の部分間に目に見える境界を生成することがあります。これは、画像のエッジスムージング（アンチエイリアス）の技術が Acrobat Reader とは異なるためです。エクスポートされたドキュメントに同じ背景画像の部分間に目に見える境界が含まれているように見える場合は、この設定を使用してその不要な効果を取り除いてください。注意！この品質の最適化は通常、変換を大幅に遅くするため、本当に必要な場合にのみこのオプションを使用してください。 |

### 例

次の例は、PDF ファイルを DOC または DOCX ファイルに変換する方法を示しています

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### 参照

* クラス [UnifiedSaveOptions](../unifiedsaveoptions/)
* インターフェース [IPipelineOptions](../ipipelineoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)