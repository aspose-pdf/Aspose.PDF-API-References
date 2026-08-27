---
title: "TeXLoadOptions クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.TeXLoadOptions クラス。TeX ファイルを PDF ドキュメントにロード/インポートするためのオプションを表します。"
type: docs
weight: 10550
url: /ja/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

TeX ファイルを PDF ドキュメントにロード/インポートするオプションを表します。

```csharp
public class TeXLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 年、月、日、時刻などの日付/時刻プリミティブの特定の値を取得/設定します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | TeX 入力ディレクトリを取得/設定します。 |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | ジョブの名前を取得/設定します。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | すべてのフォントでリガチャをキャンセルするフラグを取得/設定します。 |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | TeX 出力ディレクトリを取得/設定します。 |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 数式をラスタライズできるフラグを取得/設定します。 |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | TeX ジョブを2回実行する必要があるかどうかを示すフラグを取得/設定します。たとえば、入力 TeX ファイルに参照がある場合です。一般に、この動作はエンジンが組版プロセス中にデータを収集し、最初の実行時に補助ファイルに保存する場合に有用です。2 回目の実行時にエンジンがそのデータを使用します。 |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | TeX が必要とする入力ディレクトリを取得/設定します。必要な入力とは、メインの .tex ファイルに何らかの形でインクルードされるファイル（例：組み込みサポートがないパッケージ）です。 |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | コンソールにターミナル出力を表示するかどうかを示すフラグを取得/設定します。 |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 出力ファイルでフォントをサブセット化するかどうかを示すフラグを取得/設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | TeX のロードとコンパイルの結果を取得します。すべてが正常に完了したか、コメントやエラーがあったかを示します。 |

## 例

次の例は、TeX ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// TeX ファイルへのパスです。
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// TeXLoadOptions を初期化します\t
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// PDF ファイルを保存する
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


