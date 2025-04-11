---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions クラス。PDF ドキュメントに TeX ファイルを読み込む/インポートするためのオプションを表します
type: docs
weight: 10370
url: /ja/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions クラス

PDF ドキュメントに TeX ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public class TeXLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 年、月、日、時刻などの日時プリミティブの特定の値を取得/設定します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、ライセンスルールがこのフォントの埋め込みを無効にしていても、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | TeX 入力ディレクトリを取得/設定します。 |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | ジョブの名前を取得/設定します。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | すべてのフォントでリガチャをキャンセルするフラグを取得/設定します。 |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | TeX 出力ディレクトリを取得/設定します。 |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 数学の数式をラスタライズすることを許可するフラグを取得/設定します。 |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | 入力 TeX ファイルに参照がある場合など、TeX ジョブを 2 回実行する必要があるかどうかを示すフラグを取得/設定します。一般的に、この動作はエンジンが組版プロセスに沿ってデータを収集し、最初の実行時に補助ファイルに保存する場合に便利です。そして、2 回目の実行時に、エンジンはそのデータを何らかの形で使用します。 |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | TeX が必要とする入力ディレクトリを取得/設定します。必要な入力は、メインの .tex ファイルに何らかの形で含まれるファイルです。たとえば、組み込みサポートがないパッケージなどです。 |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。 |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は停止する必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | TeX の読み込みとコンパイルの結果を取得します - すべてがスムーズに進んだか、コメントやエラーがあったか。 |

## 例

次の例は、TeX ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)