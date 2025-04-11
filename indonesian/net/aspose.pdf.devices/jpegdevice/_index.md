---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Devices.JpegDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam jpeg
type: docs
weight: 3620
url: /id/net/aspose.pdf.devices/jpegdevice/
---
## Kelas JpegDevice

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Menginisialisasi instance baru dari kelas `JpegDevice` dengan resolusi default dan kualitas maksimum. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Menginisialisasi instance baru dari kelas `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan ukuran halaman yang diberikan, resolusi default (=150) dan kualitas maksimum. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `JpegDevice`. Resolusi untuk file gambar hasil, lihat kelas [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan dimensi gambar yang diberikan, resolusi default (=150) dan kualitas maksimum. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan ukuran halaman, resolusi dan kualitas yang diberikan. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Menginisialisasi instance baru dari kelas `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan dimensi gambar yang diberikan, resolusi dan kualitas maksimum. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan ukuran halaman, resolusi dan kualitas yang diberikan. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Menginisialisasi instance baru dari kelas `JpegDevice` dengan dimensi gambar yang diberikan, resolusi dan kualitas. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi jpeg dan menyimpannya di aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke Gambar JPEG.

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

		// Initialize JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Close stream
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

### Lihat Juga

* kelas [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)