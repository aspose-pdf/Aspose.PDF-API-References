---
title: "الفئة TiffDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Devices.TiffDevice class. تساعد هذه الفئة على حفظ مستند PDF صفحةً بصفحة في صورة tiff واحدة"
type: docs
weight: 3820
url: /ar/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

تساعد هذه الفئة على حفظ صفحات مستند pdf صفحةً بصفحة في صورة tiff واحدة.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | يُهيئ مثيلاً جديداً من الفئة `TiffDevice` بالإعدادات الافتراضية. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | يُهيئ مثيلاً جديداً من الفئة `TiffDevice`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | يحصل على إعدادات تحويل PDF إلى صورة tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | قم بعملية تحويل برادلي إلى ثنائي لتدفق الإدخال. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | يعالج المستند بالكامل ويحفظ النتائج في تدفق. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | يعالج المستند بالكامل ويحفظ النتائج في ملف. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | يحوّل صفحات معينة من المستند إلى صيغة TIFF ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | يعالج صفحات معينة من المستند ويحفظ النتائج في الملف. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف PDF إلى صور TIFF.

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
		
		// إنشاء كائن TiffSettings
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// إنشاء جهاز TIFF
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// تحويل مستند PDF إلى صورة TIFF
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### انظر أيضًا

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


