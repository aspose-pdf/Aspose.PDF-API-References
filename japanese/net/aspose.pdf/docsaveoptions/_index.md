---
title: "クラス DocSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.DocSaveOptions クラス。Doc 形式へのエクスポート用の保存オプション"
type: docs
weight: 3870
url: /ja/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Doc 形式へのエクスポート用保存オプション

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | 段落または改行を使用する |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | ソースと宛先のフォーマットペアに対してバッチ変換が適用可能な場合のバッチサイズを定義します。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Type3 フォントの変換を取得または設定します。Type 3 フォントでは、グリフはグラフィック演算子のストリームで定義されます。これにより、DOC/DOCX 出力ではテキストの代わりに画像が表示されます。このフラグを true に設定すると、Type3 フォントを TTF に変換し、結果ファイルでテキストを取得できます。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 出力形式 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 変換された画像の X 解像度。 |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 変換された画像の Y 解像度。 |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | このパラメータはテキスト行を段落にグループ化するために使用されます。2 つの相対的なテキスト行の間隔を決定します。テキスト行の高さの百分率（100 分の単位）で指定します。 |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | メモリ保存モードで変換する際に一時データを保持するパス（ファイル名またはディレクトリ名）を定義します。 |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 認識モード。 |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 箇条書きの認識をオンにする |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Pdf では、単語が文字や音節を個別に印刷する演算子で内部的に表現されることがあります。そのため、単語を検出する際には、実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱うべき幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。ATTENTION! この設定は、フォントから最適値を算出できない、非常に稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。 |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | フォントの再保存手順を取得または設定します。true に設定すると、前のフォントプロパティの影響を避けるために各ページでフォントを再読み込みし、新しく作成されたフォントを最初からロードします。パフォーマンスを向上させたい場合は、このオプションを false に設定してください。既定値は true です。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | このハンドラは変換の進捗イベントを処理するために使用できます。たとえば、プログレスバーや現在処理中のページ数を示すメッセージの表示に利用できます。コンソールに進捗を表示するハンドラのコード例は以下の通りです： |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

### 例

以下の例は、PDF ファイルを DOC または DOCX ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF ファイルへのパスです。
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// DOC または DOCX ファイルの出力パス。
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// 認識モードを Flow に設定する
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// 水平近接を 2.5 に設定する
			RelativeHorizontalProximity = 2.5f,
			// 変換プロセス中に箇条書きを認識する値を有効にする
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

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


