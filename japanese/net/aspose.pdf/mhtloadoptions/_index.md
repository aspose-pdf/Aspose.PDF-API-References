---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MhtLoadOptions クラス。PDF ドキュメントに .mht ファイルを読み込む/インポートするためのオプションを表します
type: docs
weight: 6970
url: /ja/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions クラス

PDF ドキュメントに .mht ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、ライセンスルールがこのフォントの埋め込みを無効にしていても、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | ドキュメントのページ情報を取得または設定します |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は中止されるべきです。 |

## 例

次の例は、MHT ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)