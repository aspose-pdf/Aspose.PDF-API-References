---
title: "クラス EmfDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.EmfDevice クラス。pdf ドキュメントのページを emf に保存するのに役立つ画像デバイスを表します。"
type: docs
weight: 3700
url: /ja/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

PDF ドキュメントのページを EMF 形式で保存するのに役立つ画像デバイスを表します。

```csharp
public sealed class EmfDevice : ImageDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | `EmfDevice` クラスの新しいインスタンスを、emf に書き込まれるラスタ画像のデフォルト解像度で初期化します。 |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | `EmfDevice` クラスの新しいインスタンスを、指定されたページサイズと、emf に書き込まれるラスタ画像のデフォルト解像度（=150）で初期化します。 |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | `EmfDevice` クラスの新しいインスタンスを初期化します。emf に書き込まれるラスタ画像の解像度については、[`Resolution`](../resolution/) クラスをご覧ください。 |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | `EmfDevice` クラスの新しいインスタンスを、指定された画像サイズと、emf に書き込まれるラスタ画像のデフォルト解像度（=150）で初期化します。 |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを、指定されたページサイズと、emf に書き込まれるラスタ画像の解像度で初期化します。 |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | [`JpegDevice`](../jpegdevice/) クラスの新しいインスタンスを、指定された画像サイズと、emf に書き込まれるラスタ画像の解像度で初期化します。 |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | ページを emf に変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |

## 例

次の例は、PDF ファイルを EMF 画像に変換する方法を示しています。

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

		// EmfDevice を初期化 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// 特定のページを変換し、画像をストリームに保存します。
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// ストリームを閉じる
				emfStream.Close();
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
	
		' Initialize EmfDevice   
		Dim emfDevice As EmfDevice = New EmfDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using emfStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.emf", FileMode.Create)
			
				' Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages(pageCount), emfStream)

				' Close stream
				emfStream.Close()
			End Using
		Next
	End Using
```

### 関連項目

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


