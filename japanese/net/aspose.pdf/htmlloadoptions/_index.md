---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions クラス。PDF ドキュメントに HTML ファイルを読み込む/インポートするためのオプションを表します。
type: docs
weight: 5530
url: /ja/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions クラス

PDF ドキュメントに HTML ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | 空のベースパスで HTML を PDF ドキュメントに変換するための読み込みオプションを作成します。 |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | 定義されたベースパスで HTML を PDF ドキュメントに変換するための読み込みオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML ファイルのベースパス/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みがライセンスルールで無効になっている場合でも、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | レンダリング中に使用される可能性のあるメディアタイプを取得または設定します。 |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | パース時にこのドキュメントに使用されるエンコーディングを指定する属性を取得または設定します。この属性が null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。 |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | 結果のドキュメントへのフォントの埋め込みを取得または設定します。 |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | CSS で定義された @page ルールが PageInfo で定義された値を上書きすることを指定するフラグを取得または設定します。 |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | ドキュメント全体を単一ページにレンダリングするかどうかを取得または設定します。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | ドキュメントのページ情報を取得または設定します。 |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | レイアウトオプションを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は停止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | 時には、外部リソース（画像や CSS など）の内部ローダーの使用を避け、要求されたリソースをどこかから取得するカスタムメソッドを提供する必要があります。たとえば、Aspose.PDF をクラウドで使用する場合、参照されたファイルへの直接アクセスは不可能です。このような場合、特別なメソッドにカスタムコードを入れ、そのメソッドを参照するデリゲートをこの属性に割り当てる必要があります。 |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | HTML で参照される外部データの読み込みに資格情報が必要な場合、これらの資格情報をこのパラメータに入れることができます。外部リソースの読み込み中に使用されます。 |

## 例

次の例は、HTML ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
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

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)