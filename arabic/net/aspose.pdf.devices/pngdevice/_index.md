---
title: "الفئة PngDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Devices.PngDevice. تمثل جهاز صورة يساعد على حفظ صفحات مستند pdf كملفات png."
type: docs
weight: 3770
url: /ar/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة png.

```csharp
public sealed class PngDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | يُنشئ مثيلاً جديدًا لفئة `PngDevice` باستخدام الدقة الافتراضية. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | يُنشئ مثيلاً جديدًا لفئة `PngDevice` بحجم الصفحة المقدم، والدقة الافتراضية (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | يُنشئ مثيلاً جديدًا لفئة `PngDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | يُنشئ مثيلاً جديدًا لفئة `PngDevice` بأبعاد الصورة المقدمة، والدقة الافتراضية (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | يُنشئ مثيلاً جديدًا لفئة `PngDevice` بحجم الصفحة والدقة المقدمة. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | يُنشئ مثيلاً جديدًا لفئة `PngDevice` بأبعاد الصورة والدقة المقدمة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يعيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox كإعداد افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | يحصل أو يضبط ما إذا كانت الصورة ذات خلفية شفافة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | يحوّل الصفحة إلى Bitmap. |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى PNG ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى صور PNG.

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

		// تهيئة PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// تحويل صفحة معينة وحفظ الصورة إلى التدفق
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// إغلاق التدفق
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

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


