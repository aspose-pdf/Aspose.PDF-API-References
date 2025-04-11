---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.GifDevice クラス。PDF ドキュメントのページを GIF に保存するのに役立つ画像デバイスを表します。
type: docs
weight: 3600
url: /ja/net/aspose.pdf.devices/gifdevice/
---
## GifDevice クラス

PDF ドキュメントのページを GIF に保存するのに役立つ画像デバイスを表します。

```csharp
public sealed class GifDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | デフォルト解像度で `GifDevice` クラスの新しいインスタンスを初期化します。 |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | 提供されたページサイズで `GifDevice` クラスの新しいインスタンスを初期化し、デフォルト解像度 (=150) を使用します。 |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | `GifDevice` クラスの新しいインスタンスを初期化します。 結果画像ファイルの解像度については、[`Resolution`](../resolution/) クラスを参照してください。 |
| [GifDevice](gifdevice/#constructor_4)(int, int) | 提供された画像寸法で `GifDevice` クラスの新しいインスタンスを初期化し、デフォルト解像度 (=150) を使用します。 |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | 提供されたページサイズと解像度で `GifDevice` クラスの新しいインスタンスを初期化します。 |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | 提供された画像寸法と解像度で `GifDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | ページの座標タイプ (メディア/クロップボックス) を取得または設定します。デフォルトでは CropBox 値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | フォームのプレゼンテーションモードを取得または設定します。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 画像出力の高さを取得します。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 画像の解像度を取得します。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 画像出力の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | ページを GIF に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページに対していくつかの操作を実行し、結果をファイルに保存します。 |

## 例

次の例は、PDF ファイルを GIF 画像に変換する方法を示しています。

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);

		// Initialize GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Close stream
				gifStream.Close();
			}
		}
	}
```

```csharp
[VB.NET]

    ' The path to your PDF Directory
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The file name of the PDF
    Dim pdfFile As String = "YOUR_PDF_FILE"
 
    ' Initialize instance of Document class 
	Using pdfDocument As Document = New Document(Path.Combine(dataDir, pdfFile))
		' Create Resolution object  
		Dim resolution As Resolution = New Resolution(300)
	
		' Initialize GifDevice  
		Dim gifDevice As GifDevice = New GifDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using gifStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.gif", FileMode.Create)
		   
				' Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages(pageCount), gifStream)

				' Close stream
				gifStream.Close()
			End Using
		Next
	End Using
```

### 関連項目

* クラス [ImageDevice](../imagedevice/)
* 名前空間 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* アセンブリ [Aspose.PDF](../../)