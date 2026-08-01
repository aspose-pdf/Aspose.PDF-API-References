---
title: "クラス PdfSaveOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfSaveOptions クラス。PDF 形式へのエクスポート用の保存オプションです。"
type: docs
weight: 8570
url: /ja/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Pdf 形式へのエクスポート用保存オプションです。

```csharp
public class PdfSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | フォントグリフをページ作成中にキャッシュするかどうかを示すブール値を取得または設定します。PDF を他の形式に変換する際のパフォーマンスが向上しますが、メモリ使用量が増加します。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Document がレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名です。PDF に保存されるドキュメントに、ドキュメント自体やデバイスに存在しないフォントが含まれている場合、API は（デバイス上に [`DefaultFontName`](./defaultfontname/) のフォントが見つかった場合）そのフォントをデフォルトフォントに置き換えます。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | データ保存の形式。 |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | 一時ファイルのパスです。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |

## 例

次の例は、PDF を保存する際にデフォルトフォント名を設定する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// フォントが欠落している既存の PDF ドキュメントを読み込む
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// デフォルトフォント名を指定する
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

### 関連項目

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


