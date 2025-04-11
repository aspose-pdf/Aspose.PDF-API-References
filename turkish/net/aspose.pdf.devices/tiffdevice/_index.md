---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TiffDevice sınıfı. Bu sınıf, pdf belgesini sayfa sayfa tek bir tiff görüntüsüne kaydetmeye yardımcı olur.
type: docs
weight: 3700
url: /tr/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice Sınıfı

Bu sınıf, pdf belgesini sayfa sayfa tek bir tiff görüntüsüne kaydetmeye yardımcı olur.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Varsayılan ayarlarla `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Görüntü çıktı yüksekliğini alır. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Görüntü çözünürlüğünü alır. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | PDF'yi tiff görüntüsüne eşlemek için ayarları alır. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Görüntü çıktı genişliğini alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Giriş akışı için Bradley ikileştirmesi yapar. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Tüm belgeyi işler ve sonuçları akışa kaydeder. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Tüm belgeyi işler ve sonuçları dosyaya kaydeder. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler yapar ve sonuçları dosyaya kaydeder. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Belirli belge sayfalarını tiff'e dönüştürür ve çıktıyı akışa kaydeder. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Belgenin belirli sayfalarını işler ve sonuçları dosyaya kaydeder. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını TIFF Görüntülerine dönüştürmeyi göstermektedir.

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
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
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

### Ayrıca Bakınız

* sınıf [DocumentDevice](../documentdevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)