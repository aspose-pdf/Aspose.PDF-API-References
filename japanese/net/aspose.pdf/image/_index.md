---
title: "クラス Image"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Image クラス。画像を表します。"
type: docs
weight: 5990
url: /ja/net/aspose.pdf/image/
---
## Image class

画像を表します。

```csharp
public sealed class Image : BaseParagraph
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Image](image/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | 非圧縮画像バイトを取得または設定します。 |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | 画像ビットマップのサイズを取得します。 |
| [File](../../aspose.pdf/image/file/) { get; set; } | 画像ファイルを取得または設定します。 |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | 画像ファイルのタイプを取得または設定します。 |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | 画像の高さを取得または設定します。 |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | 画像の幅を取得または設定します。 |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 段落の水平揃えを取得または設定します。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | 画像のスケールを取得または設定します。 |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | 画像ストリームを取得または設定します。 |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | 画像が生成時に解像度を使用するかどうかを示す bool 値を取得または設定します |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | 画像が白黒に強制されるかどうかを示す bool 値を取得または設定します。CCITT サブフォーマットの TIFF 画像が使用される場合、このプロパティは true に設定する必要があります。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Title](../../aspose.pdf/image/title/) { get; set; } | 画像のタイトルを示す文字列値を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | 画像をクローンします。 |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | 画像の MIME タイプを返します。 |

## 例

次の例は、画像 (PNG、JPEG、GIF、BMP、またはその他の画像形式) を PDF ファイルに変換する方法を示しています。

```csharp
[C#]
	// documents ディレクトリへのパス。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// 画像 (bmp、png、gif、jpeg など) のパスです。
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// 出力 PDF ファイルへのパス。
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//空の PDF ドキュメントを初期化します
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // サンプル画像ファイルをロードします
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // 出力 PDF ドキュメントを保存します
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

### 関連項目

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


