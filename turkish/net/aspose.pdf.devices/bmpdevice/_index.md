---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.BmpDevice sınıfı. PDF belge sayfalarını BMP formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.
type: docs
weight: 3520
url: /tr/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice sınıfı

PDF belge sayfalarını BMP formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Varsayılan çözünürlük ile `BmpDevice` sınıfının yeni bir örneğini başlatır. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Sağlanan sayfa boyutu ile `BmpDevice` sınıfının yeni bir örneğini başlatır, varsayılan çözünürlük (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | `BmpDevice` sınıfının yeni bir örneğini başlatır. Sonuç görüntü dosyası için çözünürlük, [`Resolution`](../resolution/) sınıfına bakın. |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Sağlanan görüntü boyutları ile `BmpDevice` sınıfının yeni bir örneğini başlatır, varsayılan çözünürlük (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Sağlanan sayfa boyutu ve çözünürlüğü ile `BmpDevice` sınıfının yeni bir örneğini başlatır. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Sağlanan görüntü boyutları ve çözünürlüğü ile `BmpDevice` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Görüntü çıktı yüksekliğini alır. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Görüntü çözünürlüğünü alır. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Görüntü çıktı genişliğini alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Sayfayı BMP formatına dönüştürür ve çıktı akışında kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını BMP görüntülerine dönüştürmenin nasıl yapılacağını göstermektedir.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);

		// initialize BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Close stream
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

### Ayrıca Bakınız

* sınıf [ImageDevice](../imagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)