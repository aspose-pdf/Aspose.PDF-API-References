---
title: "クラス MdLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.MdLoadOptions クラス。Markdown 形式変換のためのロードオプション。"
type: docs
weight: 7080
url: /ja/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions class

Markdown 形式変換のロードオプションです。

```csharp
public class MdLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | @page ルールが CSS で定義された場合、PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | ドキュメントのページ情報を取得または設定します |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## 例

以下の例は MD ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// MD ファイルへのパス。
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// MdLoadOptions を初期化します。
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// PDF ファイルを保存する
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


