---
title: "クラス HtmlLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlLoadOptions クラス。HTML ファイルを PDF ドキュメントにロード/インポートするためのオプションを表します"
type: docs
weight: 5660
url: /ja/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

HTML ファイルを pdf document にロード/インポートするオプションを表します。

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | 空のベースパスで HTML を PDF ドキュメントに変換するためのロードオプションを作成します。 |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | 定義されたベースパスで HTML を PDF ドキュメントに変換するためのロードオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML ファイルの基本パス/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | レンダリング中に使用される可能なメディアタイプを取得または設定します。 |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | 解析時にこのドキュメントで使用されるエンコーディングを指定する属性を取得または設定します。この属性が null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。 |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | 結果ドキュメントへのフォント埋め込みを取得または設定します |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | @page ルールが CSS で定義された場合、PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。 |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | ドキュメント全体を単一ページにレンダリングするかどうかを取得または設定します |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | ドキュメントのページ情報を取得または設定します |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | レイアウトオプションを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | 場合によっては、画像や CSS などの外部リソースの内部ローダーの使用を回避し、要求されたリソースを取得するカスタムメソッドを提供する必要があります。たとえば、クラウド環境で Aspose.PDF を使用する際、参照ファイルへの直接アクセスが不可能な場合は、特別なメソッドに配置したカスタムコードを使用し、そのメソッドを参照するデリゲートをこの属性に割り当てる必要があります。 |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | HTML で参照される外部データの読み込みに認証情報が必要な場合は、このパラメータに設定できます。外部リソースの読み込み時に使用されます。 |

## 例

以下の例は HTML ファイルを PDF ファイルに変換する方法を示しています

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// HTML ファイルへのパス。
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// HtmlLoadOptions を初期化します	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// PDF ファイルを保存する
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


