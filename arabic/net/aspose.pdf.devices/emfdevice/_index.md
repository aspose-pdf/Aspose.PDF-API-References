---
title: "الفئة EmfDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Devices.EmfDevice. تمثل جهاز صورة يساعد على حفظ صفحات مستند pdf إلى emf"
type: docs
weight: 3700
url: /ar/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `EmfDevice` مع الدقة الافتراضية لصورة النقطية المكتوبة إلى emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | يقوم بتهيئة نسخة جديدة من الفئة `EmfDevice` بحجم صفحة محدد، ودقة افتراضية لصورة النقطية المكتوبة إلى emf (=150). |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | يقوم بتهيئة نسخة جديدة من الفئة `EmfDevice`. الدقة لصورة النقطية المكتوبة إلى emf، راجع فئة [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | يقوم بتهيئة نسخة جديدة من الفئة `EmfDevice` بأبعاد صورة محددة، ودقة افتراضية لصورة النقطية المكتوبة إلى emf (=150). |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة نسخة جديدة من الفئة [`JpegDevice`](../jpegdevice/) بحجم صفحة محدد، ودقة لصورة النقطية المكتوبة إلى emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة نسخة جديدة من الفئة [`JpegDevice`](../jpegdevice/) بأبعاد صورة محددة، ودقة لصورة النقطية المكتوبة إلى emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى emf ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى صور EMF.

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

		// تهيئة EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// تحويل صفحة معينة وحفظ الصورة إلى التدفق
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// إغلاق التدفق
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

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


