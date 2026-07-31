---
title: "Kelas PngDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.PngDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke png"
type: docs
weight: 3770
url: /id/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format png.

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
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Mengonversi page menjadi Bitmap. |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi png dan menyimpannya di aliran keluaran. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke Gambar PNG.

```csharp
[C#]
	// Path ke Direktori PDF Anda
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Nama file PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Inisialisasi instance kelas Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Buat objek Resolution 	
		Resolution resolution = new Resolution(300);

		// Inisialisasi PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Konversi halaman tertentu dan simpan gambar ke aliran
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Tutup aliran
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

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


