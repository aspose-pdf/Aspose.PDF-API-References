---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions クラス。Pdf 形式へのエクスポートのための保存オプション
type: docs
weight: 8430
url: /ja/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions クラス

Pdf 形式へのエクスポートのための保存オプション

```csharp
public class PdfSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | aps ページを準備する際にフォントグリフがキャッシュされるかどうかを示すブール値を取得または設定します。PDFから他の形式への変換のパフォーマンスを向上させますが、メモリ消費が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | ドキュメントがレスポンスに保存された後、Response オブジェクトが閉じられるかどうかを示すブール値を取得または設定します。 |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | コンピュータに存在しないフォントのデフォルトで使用されるフォント名。保存されたPDFドキュメントに、ドキュメント自体およびデバイスで利用できないフォントが含まれている場合、APIはこのフォントをデフォルトフォント（デバイス上に [`DefaultFontName`](./defaultfontname/) が見つかった場合）に置き換えます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | 一時ファイルのパス。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandlerは、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションであり、保存操作は続行されますが、ユーザーは Abort を返すこともでき、その場合保存操作は中止されるべきです。 |

## 例

以下の例は、PDFを保存する際にデフォルトのフォント名を設定する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### 参照

* クラス [SaveOptions](../saveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)