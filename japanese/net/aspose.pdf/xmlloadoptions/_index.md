---
title: "クラス XmlLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XmlLoadOptions クラス。XML ファイルを PDF ドキュメントにロード/インポートするためのオプションを表します。"
type: docs
weight: 11580
url: /ja/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

XML ファイルを pdf ドキュメントにロード/インポートするオプションを表します。

```csharp
public class XmlLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | `XmlLoadOptions` オブジェクトを XSL データなしで作成します。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | `XmlLoadOptions` オブジェクトを XSL データ付きで作成します。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | `XmlLoadOptions` オブジェクトを XSL データ付きで作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML を PDF ドキュメントに変換するための XSL データを取得します。 |

## 例

次の例は XML ファイルを PDF ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// XML ファイルへのパスです。
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// XmlLoadOptions を初期化	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// XML ファイルを保存
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


