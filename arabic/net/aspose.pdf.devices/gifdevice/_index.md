---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.GifDevice. تمثل جهاز الصورة الذي يساعد على حفظ صفحات مستند PDF في صيغة GIF
type: docs
weight: 3600
url: /ar/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

تمثل جهاز الصورة الذي يساعد على حفظ صفحات مستند PDF في صيغة GIF.

```csharp
public sealed class GifDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `GifDevice` بدقة افتراضية. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `GifDevice` بحجم الصفحة المقدم، بدقة افتراضية (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `GifDevice`. دقة ملف الصورة الناتج، انظر إلى فئة [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد من فئة `GifDevice` بأبعاد الصورة المقدمة، بدقة افتراضية (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة `GifDevice` بحجم الصفحة والدقة المقدمة. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة `GifDevice` بأبعاد الصورة والدقة المقدمة. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (Media/Crop boxes). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع عرض النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى GIF ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Examples

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور GIF.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)