---
title: Class ApsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ApsLoadOptions クラス。クラスは aps ロードオプションを説明します
type: docs
weight: 2750
url: /ja/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions クラス

クラスは aps ロードオプションを説明します。

```csharp
public class ApsLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、ライセンスルールがこのフォントの埋め込みを無効にしていても、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、ロード操作は続行されますが、ユーザーが Abort を返すこともでき、その場合はロード操作を中止する必要があります。 |

## 例

次の例は、APS ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your APS File.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initialize ApsLoadOptions  	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initialize Document wiht ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)