---
title: "Kelas BmpDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.BmpDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke bmp"
type: docs
weight: 3640
url: /id/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Menginisialisasi instance baru dari kelas `BmpDevice` dengan resolusi default. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `BmpDevice` dengan ukuran halaman yang diberikan, resolusi default (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `BmpDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `BmpDevice` dengan dimensi gambar yang diberikan, resolusi default (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `BmpDevice` dengan ukuran halaman dan resolusi yang diberikan. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `BmpDevice` dengan dimensi gambar dan resolusi yang diberikan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Mendapatkan tinggi output gambar. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Mendapatkan resolusi gambar. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Mendapatkan lebar output gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Mengonversi page menjadi Bitmap. |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi bmp dan menyimpannya ke aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke gambar BMP.

```csharp
[C#]
	// Path ke Direktori PDF Anda
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Nama file PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// inisialisasi instance dari kelas Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Buat objek Resolution 	
		Resolution resolution = new Resolution(300);

		// inisialisasi BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Konversi halaman tertentu dan simpan gambar ke aliran
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Tutup aliran
				bmpStream.Close();
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
		
		' Initialize BmpDevice  
		Dim bmpDevice As BmpDevice = New BmpDevice(resolution)
		
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using bmpStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.bmp", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages(pageCount), bmpStream)

				' Close stream
				bmpStream.Close()
			End Using
		Next
	End Using
```

### Lihat Juga

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


