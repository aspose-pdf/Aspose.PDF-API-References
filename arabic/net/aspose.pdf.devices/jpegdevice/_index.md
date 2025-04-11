---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.JpegDevice. تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في تنسيق JPEG
type: docs
weight: 3620
url: /ar/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في تنسيق JPEG.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` بدقة افتراضية وجودة قصوى. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع حجم الصفحة المقدم، دقة افتراضية (=150) وجودة قصوى. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice`.  الدقة لملف الصورة الناتج، انظر فئة [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع أبعاد الصورة المقدمة، دقة افتراضية (=150) وجودة قصوى. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع حجم الصفحة المقدم، الدقة وجودة قصوى. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع أبعاد الصورة المقدمة، الدقة وجودة قصوى. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع حجم الصفحة المقدم، الدقة والجودة. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | يقوم بتهيئة مثيل جديد من فئة `JpegDevice` مع أبعاد الصورة المقدمة، الدقة والجودة. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى JPEG ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Examples

المثال التالي يوضح كيفية تحويل ملف PDF إلى صور JPEG.

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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)