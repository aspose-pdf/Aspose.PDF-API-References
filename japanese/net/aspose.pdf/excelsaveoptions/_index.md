---
title: "クラス ExcelSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ExcelSaveOptions クラス。Excel 形式へのエクスポート用の保存オプションです。"
type: docs
weight: 4200
url: /ja/net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class

Excel 形式へのエクスポート用保存オプション

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | この属性は、OCR サブレイヤーを使用して PDF Document から画像またはテキストを抽出する機能を有効にします。 |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | 出力形式 |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | ワークシートの最初の列として空白列を挿入する必要がある場合は true を設定します。デフォルト値は false で、空白列は挿入されません。 |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | 結果のブックでワークシートの数を最小限に抑える必要がある場合は true を設定します。デフォルト値は false で、各 PDF ページが個別のワークシートとして保存されます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | ドキュメント全体で均一な列分割を使用する場合は true に設定します。デフォルト値は false です。これは、列の分割が各ページごとに独立することを意味します。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 数スレッドでページを処理します。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | PDF には、ページや表セルの背景画像が、同じタイル背景画像を複数組み合わせて隣接させて構成されていることがあります。そのような場合、対象フォーマットのレンダラ（例：DOCS 形式の MsWord）では、背景画像の各部分間に目に見える境界が生成されることがあります。これは、画像エッジの平滑化（アンチエイリアス）手法が Acrobat Reader と異なるためです。エクスポートされた文書に同じ背景画像の部分間に目に見える境界があるように見える場合は、この設定を使用して不要な効果を取り除いてください。注意！この品質最適化は通常、変換速度を大幅に低下させるため、実際に必要なときにのみこのオプションを使用してください。 |

## 例

以下の例は、PDF ファイルを XLS または XLSX ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF ファイルへのパスです。
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// 出力する xls または xlsx ファイルへのパスです。
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// ExcelSaveOptions を初期化します	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// xls または xlsx ファイルを保存
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### 関連項目

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


