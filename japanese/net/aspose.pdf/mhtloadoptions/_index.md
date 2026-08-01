---
title: "Class MhtLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.MhtLoadOptions クラス。.mht ファイルを PDF ドキュメントに読み込み/インポートするオプションを表します"
type: docs
weight: 7110
url: /ja/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions class

.mht ファイルを pdf document にロード/インポートするオプションを表します。

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | ドキュメントのページ情報を取得または設定します |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## 例

次の例は、MHT ファイルを PDF ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// MHT ファイルへのパスです。
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// MhtLoadOptions を初期化します\t
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// PDF ファイルを保存する
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
	
### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


