---
title: "الفئة BmpDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Devices.BmpDevice. تمثل جهاز صورة يساعد على حفظ صفحات مستند pdf كملفات bmp"
type: docs
weight: 3640
url: /ar/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | يُنشئ مثيلاً جديدًا لفئة `BmpDevice` باستخدام الدقة الافتراضية. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | يُنشئ مثيلاً جديدًا لفئة `BmpDevice` بحجم الصفحة المقدم، والدقة الافتراضية (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | يُنشئ مثيلاً جديدًا لفئة `BmpDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | يُنشئ مثيلاً جديدًا لفئة `BmpDevice` بأبعاد الصورة المقدمة، والدقة الافتراضية (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | يُنشئ مثيلاً جديدًا لفئة `BmpDevice` بحجم الصفحة والدقة المقدمة. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | يُنشئ مثيلاً جديدًا لفئة `BmpDevice` بأبعاد الصورة والدقة المقدمة. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | يحوِّل الصفحة إلى bmp ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور BMP.

```csharp
[C#]
	// المسار إلى دليل PDF الخاص بك
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// اسم ملف PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// تهيئة مثيل لفئة Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// إنشاء كائن Resolution \t
		Resolution resolution = new Resolution(300);

		// تهيئة BmpDevice\t
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// تحويل صفحة معينة وحفظ الصورة إلى التدفق
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// إغلاق التدفق
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

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


