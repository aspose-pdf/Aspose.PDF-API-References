---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlLoadOptions クラス。PDF ドキュメントに XML ファイルを読み込む/インポートするためのオプションを表します。
type: docs
weight: 11390
url: /ja/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions クラス

PDF ドキュメントに XML ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public class XmlLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | xsl データなしで `XmlLoadOptions` オブジェクトを作成します。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | xsl データを持つ `XmlLoadOptions` オブジェクトを作成します。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | xsl データを持つ `XmlLoadOptions` オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、ライセンスルールがこのフォントの埋め込みを無効にしていても、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は中止されるべきです。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML を PDF ドキュメントに変換するための xsl データを取得します。 |

## 例

以下の例は、XML ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)