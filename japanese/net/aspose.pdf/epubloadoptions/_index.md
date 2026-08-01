---
title: "クラス EpubLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.EpubLoadOptions クラス。EPUB ファイルを PDF Document にロード/インポートするためのオプションを含みます。"
type: docs
weight: 4170
url: /ja/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

PDF ドキュメントに EPUB ファイルをロード/インポートするためのオプションを含みます。

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | EPUB ファイルを PDF Document に変換するためのデフォルトのロードオプションを作成します。デフォルトの PDF ページサイズは A4、300dpi、2480 × 3508 です。 |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 指定されたページサイズでロードオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Epub Document を開く際に適用するカスタム CSS を取得または設定します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | 余白情報を表すオブジェクトへの参照を取得します。 |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | インポート用の出力ページサイズを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | 余白領域の使用モードを表します。インポートされた Document の CSS における余白の使用に関する指示（存在する場合）の取り扱いを定義します。 |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 注意！この機能は実装されていますが、サンプル Document の OSHARED レイヤーでのブロッカー問題が判明したため、まだ公開 API に含められていません。ページサイズの使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計であるため、必要なページサイズに合わせることが可能です。しかし、コンテンツが指定された水平位置やサイズを持ち、要求されたページサイズに収まらない場合があります。そのような場合、コンテンツのサイズが結果 PDF Document の初期ページサイズに合わないときに何をすべきかを定義できます。 |

## 例

以下の例は、EPUB ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// EPUB ファイルへのパス。
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// EpubLoadOptions を初期化する 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// PDF ファイルを保存する
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

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


