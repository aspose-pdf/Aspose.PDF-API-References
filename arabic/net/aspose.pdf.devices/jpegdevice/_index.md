---
title: "الفئة JpegDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Devices.JpegDevice. تمثّل جهاز صورة يساعد على حفظ صفحات مستند PDF إلى jpeg"
type: docs
weight: 3740
url: /ar/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | ينشئ مثيلاً جديداً لفئة `JpegDevice` بالدقة الافتراضية وأعلى جودة. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | ينشئ مثيلاً جديداً لفئة `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بحجم الصفحة المقدم، والدقة الافتراضية (=150) وأعلى جودة. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | ينشئ مثيلاً جديداً لفئة `JpegDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بأبعاد الصورة المقدمة، والدقة الافتراضية (=150) وأعلى جودة. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بحجم الصفحة المقدم، والدقة، وأعلى جودة. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | ينشئ مثيلاً جديداً لفئة `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بأبعاد الصورة المقدمة، والدقة، وأعلى جودة. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بحجم الصفحة المقدم، والدقة، والجودة. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | ينشئ مثيلاً جديداً لفئة `JpegDevice` بأبعاد الصورة المقدمة، والدقة، والجودة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يعيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox كإعداد افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | يحوّل الصفحة إلى Bitmap. |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | يحوّل الصفحة إلى JPEG ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور JPEG.

```csharp
[C#]
	// المسار إلى دليل PDF الخاص بك
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// اسم ملف PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// تهيئة نسخة من فئة Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// إنشاء كائن Resolution \t
		Resolution resolution = new Resolution(300);

		// تهيئة JpegDevice\t
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// تحويل صفحة معينة وحفظ الصورة إلى التدفق
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// إغلاق التدفق
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

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


