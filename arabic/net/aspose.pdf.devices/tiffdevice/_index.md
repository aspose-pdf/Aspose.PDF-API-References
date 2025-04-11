---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.TiffDevice. تساعد هذه الفئة على حفظ مستند PDF صفحة بصفحة في صورة TIFF واحدة
type: docs
weight: 3700
url: /ar/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

تساعد هذه الفئة على حفظ مستند PDF صفحة بصفحة في صورة TIFF واحدة.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `TiffDevice` مع الإعدادات الافتراضية. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | يقوم بتهيئة مثيل جديد من فئة `TiffDevice`. |

## Properties

| Name | Description |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع تقديم النموذج. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | يحصل على الإعدادات الخاصة بتحويل PDF إلى صورة TIFF. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | يقوم بعملية ثنائية باستخدام طريقة برادلي لتدفق الإدخال. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | يعالج المستند بالكامل ويحفظ النتائج في التدفق. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | يعالج المستند بالكامل ويحفظ النتائج في ملف. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | يقوم بتحويل صفحات معينة من المستند إلى TIFF ويحفظها في التدفق الناتج. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | يعالج صفحات معينة من المستند ويحفظ النتائج في ملف. |

## Examples

يوضح المثال التالي كيفية تحويل ملف PDF إلى صور TIFF.

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
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
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

### See Also

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)