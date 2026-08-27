---
title: "Kelas EmfDevice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Devices.EmfDevice. Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam emf"
type: docs
weight: 3700
url: /id/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Menginisialisasi instance baru dari kelas `EmfDevice` dengan resolusi default gambar raster yang ditulis ke emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Menginisialisasi instance baru dari kelas `EmfDevice` dengan ukuran halaman yang diberikan, dan resolusi default untuk gambar raster yang ditulis ke emf (=150). |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Menginisialisasi instance baru dari kelas `EmfDevice`. Resolusi untuk gambar raster yang ditulis ke emf, lihat kelas [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Menginisialisasi instance baru dari kelas `EmfDevice` dengan dimensi gambar yang diberikan, dan resolusi default untuk gambar raster yang ditulis ke emf (=150). |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan ukuran halaman yang diberikan, dan resolusi untuk gambar raster yang ditulis ke emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Menginisialisasi instance baru dari kelas [`JpegDevice`](../jpegdevice/) dengan dimensi gambar yang diberikan, dan resolusi untuk gambar raster yang ditulis ke emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Mengonversi halaman menjadi emf dan menyimpannya ke dalam aliran output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Melakukan beberapa operasi pada halaman yang diberikan dan menyimpan hasilnya ke dalam file. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF menjadi Gambar EMF.

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

		// Inisialisasi EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Konversi halaman tertentu dan simpan gambar ke aliran
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Tutup aliran
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

### Lihat Juga

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


