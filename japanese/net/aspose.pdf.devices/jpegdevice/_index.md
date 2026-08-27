---
title: "クラス JpegDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.JpegDevice クラス。PDF Document のページを jpeg に保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 3740
url: /ja/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

PDF ドキュメントのページを JPEG 形式で保存するのに役立つ画像デバイスを表します。

```csharp
public sealed class JpegDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | `JpegDevice` クラスの新しいインスタンスを、デフォルトの解像度と最大品質で初期化します。 |
| [JpegDevice](jpegdevice/#constructor_6)(int) | `JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | 指定されたページサイズ、デフォルトの解像度 (=150) および最大品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | `JpegDevice` クラスの新しいインスタンスを初期化します。結果画像ファイルの解像度については、[`Resolution`](../resolution/) クラスを参照してください。 |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | 指定された画像サイズ、デフォルトの解像度 (=150) および最大品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | 指定されたページサイズ、解像度、最大品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | `JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | 指定された画像サイズ、解像度、最大品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | 指定されたページサイズ、解像度、品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | 指定された画像サイズ、解像度、品質で、`JpegDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | フォームの表示モードを取得または設定します。 |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 画像出力の高さを取得します。 |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 画像解像度を取得します。 |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 画像出力幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Page をビットマップに変換します。 |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | ページを jpeg に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

## 例

次の例は、PDF ファイルを JPEG 画像に変換する方法を示しています。

```csharp
[C#]
	// PDFディレクトリへのパス
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// PDFのファイル名
	string pdfFile = @"YOUR_PDF_FILE";

	// Documentクラスのインスタンスを初期化します
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Resolutionオブジェクトを作成します 	
		Resolution resolution = new Resolution(300);

		// JpegDevice を初期化	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// 特定のページを変換し、画像をストリームに保存します。
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// ストリームを閉じる
				jpegStream.Close();
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
		
		' Initialize JpegDevice
		Dim jpegDevice As JpegDevice = New JpegDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using jpegStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.jpeg", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages(pageCount), jpegStream)

				' Close stream
				jpegStream.Close()
			End Using
		Next
    End Using
```

### 関連項目

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


