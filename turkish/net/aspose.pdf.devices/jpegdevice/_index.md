---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.JpegDevice sınıfı. PDF belge sayfalarını JPEG formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.
type: docs
weight: 3620
url: /tr/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice sınıfı

PDF belge sayfalarını JPEG formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Varsayılan çözünürlük ve maksimum kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Sağlanan sayfa boyutu, varsayılan çözünürlük (=150) ve maksimum kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | `JpegDevice` sınıfının yeni bir örneğini başlatır. Sonuç görüntü dosyası için çözünürlük, [`Resolution`](../resolution/) sınıfına bakın. |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Sağlanan görüntü boyutları, varsayılan çözünürlük (=150) ve maksimum kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Sağlanan sayfa boyutu, çözünürlük ve maksimum kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Sağlanan görüntü boyutları, çözünürlük ve maksimum kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Sağlanan sayfa boyutu, çözünürlük ve kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Sağlanan görüntü boyutları, çözünürlük ve kalite ile `JpegDevice` sınıfının yeni bir örneğini başlatır. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Sayfayı JPEG formatına dönüştürür ve çıktı akışında kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını JPEG görüntülerine dönüştürmenin nasıl yapılacağını göstermektedir.

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

### Ayrıca Bakınız

* sınıf [ImageDevice](../imagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)