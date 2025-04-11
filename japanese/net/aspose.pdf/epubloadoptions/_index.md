---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions クラス。PDF ドキュメントに EPUB ファイルを読み込む/インポートするためのオプションを含みます。
type: docs
weight: 4050
url: /ja/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions クラス

PDF ドキュメントに EPUB ファイルを読み込む/インポートするためのオプションを含みます。

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | EPUB ファイルを PDF ドキュメントに変換するためのデフォルトの読み込みオプションを作成します。デフォルトの PDF ページサイズ - A4 300dpi 2480 X 3508。 |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 指定されたページサイズで読み込みオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Epub ドキュメントを開くときに適用するカスタム CSS を取得または設定します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、ライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みを無効にするライセンスルールがある場合でも、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | マージン情報を表すオブジェクトへの参照を取得します。 |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | インポートの出力ページサイズを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は停止する必要があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | マージンエリアの使用モードを表します - インポートされたドキュメントの CSS に関連するマージンの使用に関する指示の扱いを定義します。 |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 注意！機能は実装されていますが、サンプルドキュメントに対して OSHARED レイヤーでブロッカーの問題が明らかになったため、まだ公開 API に追加されていません。変換中のページサイズの使用モードを表します。フォーマット（HTML、EPUB など）は通常フロートデザインを持っているため、必要なページサイズに合わせることができます。しかし、時にはコンテンツに指定された水平位置やサイズがあり、必要なページサイズにコンテンツを配置できない場合があります。その場合、結果の PDF ドキュメントの初期ページサイズに合わないコンテンツのサイズの場合に何をすべきかを定義できます。 |

## 例

次の例は、EPUB ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)