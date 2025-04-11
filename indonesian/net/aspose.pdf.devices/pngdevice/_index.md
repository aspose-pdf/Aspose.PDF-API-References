---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.PngDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam png
type: docs
weight: 3650
url: /id/net/aspose.pdf.devices/pngdevice/
---
## Kelas PngDevice

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Menginisialisasi instance baru dari kelas `PngDevice` dengan resolusi default. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `PngDevice` dengan ukuran halaman yang diberikan, resolusi default (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `PngDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `PngDevice` dengan dimensi gambar yang diberikan, resolusi default (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `PngDevice` dengan ukuran halaman dan resolusi yang diberikan. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `PngDevice` dengan dimensi gambar dan resolusi yang diberikan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Mendapatkan tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Mendapatkan atau mengatur apakah gambar memiliki latar belakang transparan. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Mendapatkan lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi png dan menyimpannya di aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF menjadi Gambar PNG.

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

		// Initialize PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Close stream
				pngStream.Close();
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
		' initialize PngDevice  

		Dim pngDevice As PngDevice = New PngDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using pngStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.png", FileMode.Create)
				' Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages(pageCount), pngStream)

				' Close stream
				pngStream.Close()
			End Using
		Next
	End Using
```

### Lihat Juga

* kelas [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)