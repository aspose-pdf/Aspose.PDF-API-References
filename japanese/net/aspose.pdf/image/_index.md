---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Image クラス。画像を表します
type: docs
weight: 5860
url: /ja/net/aspose.pdf/image/
---
## Image クラス

画像を表します。

```csharp
public sealed class Image : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Image](image/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | 圧縮されていない画像バイトを取得または設定します。 |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | 画像のビットマップサイズを取得します。 |
| [File](../../aspose.pdf/image/file/) { get; set; } | 画像ファイルを取得または設定します。 |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | 画像ファイルの種類を取得または設定します。 |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | 画像の高さを取得または設定します。 |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | 画像の幅を取得または設定します。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントのハイパーリンクを取得または設定します（PDFジェネレーター用）。 |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | 画像のスケールを取得または設定します。 |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | 画像ストリームを取得または設定します。 |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | 生成中に画像が解像度を使用するかどうかを示すブール値を取得または設定します。 |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | 画像が強制的に白黒であるかどうかを示すブール値を取得または設定します。CCITTサブフォーマットのTIFF画像が使用される場合、このプロパティはtrueに設定する必要があります。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示すブール値を取得または設定します。デフォルトはfalseです（PDF生成用）。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトはfalseです（PDF生成用）。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制するブール値を取得または設定します。デフォルトはfalseです（PDF生成用）。 |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示すブール値を取得または設定します。デフォルトはfalseです（PDF生成用）。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側のマージンを取得または設定します（PDF生成用）。 |
| [Title](../../aspose.pdf/image/title/) { get; set; } | 画像のタイトルを示す文字列値を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直揃えを取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフのZオーダーを示す整数値を取得または設定します。ZIndexが大きいグラフは、ZIndexが小さいグラフの上に配置されます。ZIndexは負の値を取ることができます。負のZIndexを持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | 画像をクローンします。 |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | 画像のMIMEタイプを返します。 |

## 例

以下の例は、画像（PNG、JPEG、GIF、BMP、またはその他の画像形式）をPDFファイルに変換する方法を示しています。

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### 参照

* クラス [BaseParagraph](../baseparagraph/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)