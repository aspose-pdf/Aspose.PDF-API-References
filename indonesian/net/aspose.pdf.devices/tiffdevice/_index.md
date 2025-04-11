---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.TiffDevice. Kelas ini membantu menyimpan dokumen pdf halaman demi halaman ke dalam satu gambar tiff
type: docs
weight: 3700
url: /id/net/aspose.pdf.devices/tiffdevice/
---
## Kelas TiffDevice

Kelas ini membantu menyimpan dokumen pdf halaman demi halaman ke dalam satu gambar tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Menginisialisasi instance baru dari kelas `TiffDevice` dengan pengaturan default. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Menginisialisasi instance baru dari kelas `TiffDevice`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Mendapatkan tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Mendapatkan pengaturan untuk memetakan pdf ke dalam gambar tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Mendapatkan lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Melakukan binarisasi Bradley untuk aliran input. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Memproses seluruh dokumen dan menyimpan hasilnya ke dalam aliran. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Memproses seluruh dokumen dan menyimpan hasilnya ke dalam file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Mengonversi halaman dokumen tertentu menjadi tiff dan menyimpannya di aliran output. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Memproses halaman tertentu dari dokumen dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF menjadi Gambar TIFF.

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

### Lihat Juga

* kelas [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)