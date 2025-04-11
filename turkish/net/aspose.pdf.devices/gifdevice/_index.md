---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.GifDevice sınıfı. PDF belge sayfalarını GIF formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.
type: docs
weight: 3600
url: /tr/net/aspose.pdf.devices/gifdevice/
---
## GifDevice sınıfı

PDF belge sayfalarını GIF formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

```csharp
public sealed class GifDevice : ImageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Varsayılan çözünürlük ile `GifDevice` sınıfının yeni bir örneğini başlatır. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Sağlanan sayfa boyutu ile `GifDevice` sınıfının yeni bir örneğini başlatır, varsayılan çözünürlük (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | `GifDevice` sınıfının yeni bir örneğini başlatır. Sonuç görüntü dosyası için çözünürlük, [`Resolution`](../resolution/) sınıfına bakın. |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Sağlanan görüntü boyutları ile `GifDevice` sınıfının yeni bir örneğini başlatır, varsayılan çözünürlük (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Sağlanan sayfa boyutu ve çözünürlüğü ile `GifDevice` sınıfının yeni bir örneğini başlatır. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Sağlanan görüntü boyutları ve çözünürlüğü ile `GifDevice` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Görüntü çıktı yüksekliğini alır. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Görüntü çözünürlüğünü alır. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Görüntü çıktı genişliğini alır. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Sayfayı GIF formatına dönüştürür ve çıktı akışında kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

## Örnekler

Aşağıdaki örnek, PDF dosyasını GIF görüntülerine dönüştürmeyi göstermektedir.

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

		// Initialize GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Close stream
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

### Ayrıca Bakınız

* sınıf [ImageDevice](../imagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)