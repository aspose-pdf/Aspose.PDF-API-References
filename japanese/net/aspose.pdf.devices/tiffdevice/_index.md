---
title: "クラス TiffDevice"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Devices.TiffDevice クラス。このクラスは pdf ドキュメントのページを1ページずつ1つの TIFF 画像に保存するのに役立ちます。"
type: docs
weight: 3820
url: /ja/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

このクラスは PDF ドキュメントのページを順に 1 つの TIFF 画像に保存するのに役立ちます。

```csharp
public sealed class TiffDevice : DocumentDevice
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | `TiffDevice` クラスの新しいインスタンスをデフォルト設定で初期化します。 |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | フォームの表示モードを取得または設定します。 |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | 画像出力の高さを取得します。 |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | 画像解像度を取得します。 |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | pdf を TIFF 画像にマッピングする設定を取得します。 |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | 画像出力幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | 入力ストリームに対してブラッドリー二値化を実行します。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | ドキュメント全体を処理し、結果をストリームに保存します。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | ドキュメント全体を処理し、結果をファイルに保存します。 |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 指定されたページで何らかの操作を実行し、結果をファイルに保存します。 |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | 特定のドキュメントページをTIFFに変換し、出力ストリームに保存します。 |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | ドキュメントの特定のページを処理し、結果をファイルに保存します。 |

## 例

次の例は、PDFファイルをTIFF画像に変換する方法を示しています。

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
		
		// TiffSettingsオブジェクトを作成します
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// TIFFデバイスを作成します
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// PDFドキュメントをTIFF画像に変換します
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### 関連項目

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


