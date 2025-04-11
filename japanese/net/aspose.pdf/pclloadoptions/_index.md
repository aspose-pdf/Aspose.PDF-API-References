---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PclLoadOptions クラス。PDF ドキュメントに PCL ファイルを読み込むためのオプションを表します。
type: docs
weight: 8300
url: /ja/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions クラス

PDF ドキュメントに PCL ファイルを読み込む（インポートする）ためのオプションを表します。

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | ソースと宛先フォーマットのペアにバッチ変換が適用可能な場合のバッチサイズを定義します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようにします。たとえば、このフォントの埋め込みがライセンスルールによって無効にされている場合でも、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は中止されるべきです。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | 変換に使用される変換エンジンを定義します。 |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | 変換エラーのリスト。 |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | PCL 変換エラーを抑制するかどうかを示すブール値を取得または設定します。 |

## 例

以下の例は、PCL ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 参照

* クラス [LoadOptions](../loadoptions/)
* インターフェース [IPipelineOptions](../ipipelineoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)