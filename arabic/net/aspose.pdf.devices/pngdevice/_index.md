---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.PngDevice. تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في PNG
type: docs
weight: 3650
url: /ar/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في PNG.

```csharp
public sealed class PngDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `PngDevice` بدقة افتراضية. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `PngDevice` بحجم الصفحة المقدم، بدقة افتراضية (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `PngDevice`. دقة ملف الصورة الناتج، انظر فئة [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد من فئة `PngDevice` بأبعاد الصورة المقدمة، بدقة افتراضية (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة `PngDevice` بحجم الصفحة المقدم والدقة. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة `PngDevice` بأبعاد الصورة المقدمة والدقة. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (صناديق الوسائط/القص). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع تقديم النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | يحصل أو يحدد ما إذا كانت الصورة تحتوي على خلفية شفافة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى PNG ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Examples

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور PNG.

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

		// Initialize PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Close stream
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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)