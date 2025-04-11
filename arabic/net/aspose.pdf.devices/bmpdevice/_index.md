---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.BmpDevice. تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في BMP
type: docs
weight: 3520
url: /ar/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في BMP.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `BmpDevice` بدقة افتراضية. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `BmpDevice` بحجم الصفحة المقدم، بدقة افتراضية (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `BmpDevice`. دقة ملف الصورة الناتج، انظر فئة [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد من فئة `BmpDevice` بأبعاد الصورة المقدمة، بدقة افتراضية (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة `BmpDevice` بحجم الصفحة المقدم والدقة. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة `BmpDevice` بأبعاد الصورة المقدمة والدقة. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (صناديق الوسائط/القص). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع تقديم النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى BMP ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Examples

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور BMP.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)