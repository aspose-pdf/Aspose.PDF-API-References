---
title: "Kelas GifDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "kelas Aspose.Pdf.Devices.GifDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke gif"
type: docs
weight: 3720
url: /id/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Menginisialisasi instance baru dari kelas `GifDevice` dengan resolusi default. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `GifDevice` dengan ukuran halaman yang diberikan, resolusi default (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `GifDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `GifDevice` dengan dimensi gambar yang diberikan, resolusi default (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `GifDevice` dengan ukuran halaman dan resolusi yang diberikan. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `GifDevice` dengan dimensi gambar dan resolusi yang diberikan. |

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
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi gif dan menyimpannya di aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF menjadi Gambar GIF.

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

		// Inisialisasi GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Konversi halaman tertentu dan simpan gambar ke aliran
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Tutup aliran
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

### Lihat Juga

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


