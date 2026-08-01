---
title: "クラス PdfXmlLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfXmlLoadOptions クラス。PdfXml 形式のロードオプション"
type: docs
weight: 8590
url: /ja/net/aspose.pdf/pdfxmlloadoptions/
---
## PdfXmlLoadOptions class

PdfXml 形式のロードオプションです。

```csharp
public class PdfXmlLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfXmlLoadOptions](pdfxmlloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## 例

次の例は PDFXML ファイルを PDF ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// PDFXML ファイルへのパスです。
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// PdfXmlLoadOptions を初期化します	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// PDF ファイルを保存する
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDFXML File.
    Dim pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf")
 
    ' Initialize PdfXmlLoadOptions  
    Dim pdfXmlLoadOptions As PdfXmlLoadOptions = New PdfXmlLoadOptions()
 
    Using pdfDocument As Document = New Document(pdfXmlFile, pdfXmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


