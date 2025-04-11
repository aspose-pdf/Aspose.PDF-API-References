---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.EmfDevice. تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في EMF
type: docs
weight: 3580
url: /ar/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

تمثل جهاز الصورة الذي يساعد في حفظ صفحات مستند PDF في EMF.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `EmfDevice` بدقة افتراضية للصورة النقطية المكتوبة في EMF. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `EmfDevice` بحجم الصفحة المقدم، ودقة افتراضية للصورة النقطية المكتوبة في EMF (=150) |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `EmfDevice`. دقة الصورة النقطية المكتوبة في EMF، انظر فئة [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد من فئة `EmfDevice` بأبعاد الصورة المقدمة، ودقة افتراضية للصورة النقطية المكتوبة في EMF (=150) |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) بحجم الصفحة المقدم، ودقة الصورة النقطية المكتوبة في EMF. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) بأبعاد الصورة المقدمة، ودقة الصورة النقطية المكتوبة في EMF. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل على نوع إحداثيات الصفحة (صناديق الوسائط/القص). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل على وضع عرض النموذج أو يحدده. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل على خيارات العرض أو يحددها. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى EMF ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Examples

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور EMF.

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

		// Initialize EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Close stream
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

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)