---
title: "الفئة GifDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Devices.GifDevice. تمثل جهاز صورة يساعد على حفظ صفحات مستند pdf كملفات gif"
type: docs
weight: 3720
url: /ar/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | يُنشئ مثيلًا جديدًا للفئة `GifDevice` بدقة افتراضية. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | يُنشئ مثيلًا جديدًا للفئة `GifDevice` بحجم صفحة محدد، ودقة افتراضية (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | يُنشئ مثيلًا جديدًا للفئة `GifDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | يُنشئ مثيلًا جديدًا للفئة `GifDevice` بأبعاد صورة محددة، ودقة افتراضية (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | يُنشئ مثيلًا جديدًا للفئة `GifDevice` بحجم صفحة ودقة محددة. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | يُنشئ مثيلًا جديدًا للفئة `GifDevice` بأبعاد صورة ودقة محددة. |

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
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | يحوّل الصفحة إلى gif ويحفظها في دفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى صور GIF.

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

		// تهيئة GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// تحويل صفحة معينة وحفظ الصورة إلى التدفق
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// إغلاق التدفق
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

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


