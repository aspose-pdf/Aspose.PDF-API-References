---
title: Class Image
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Image. تمثل الصورة
type: docs
weight: 5860
url: /ar/net/aspose.pdf/image/
---
## فئة الصورة

تمثل الصورة.

```csharp
public sealed class Image : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Image](image/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | يحصل أو يحدد بايت الصورة غير المضغوطة. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | يحصل على حجم صورة البت ماب. |
| [File](../../aspose.pdf/image/file/) { get; set; } | يحصل أو يحدد ملف الصورة. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | يحصل أو يحدد نوع ملف الصورة. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | يحصل أو يحدد ارتفاع الصورة. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | يحصل أو يحدد عرض الصورة. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الفقرة (لإنشاء PDF). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | يحصل أو يحدد مقياس الصورة. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | يحصل أو يحدد تدفق الصورة. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الصورة مجبرة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من نوع CCITT الفرعي، يجب تعيين هذه الخاصية إلى true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | يحصل أو يحدد قيمة سلسلة تشير إلى عنوان الصورة. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | استنساخ الصورة. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | يعيد نوع MIME للصورة. |

## أمثلة

تظهر المثال التالي كيفية تحويل الصور (PNG، JPEG، GIF، BMP، أو تنسيقات الصور الأخرى) إلى ملف PDF.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your image (bmp, png, gif, jpeg, etc.) File.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//Initialize empty PDF document
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // Load sample image file
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // Save output PDF document
	  pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir = "YOUR_DATA_DIRECTORY"

    ' The path to your image (bmp, png, gif, jpeg, etc.) File.
    Dim imageFile = Path.Combine(dataDir, "Image-to-PDF.png")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf")
 
    'Initialize empty PDF document
    Using pdfDocument As Document = New Document()
        pdfDocument.Pages.Add()
        Dim image As Image = New Image()
 
        ' Load sample image file
        image.File = imageFile
        pdfDocument.Pages(1).Paragraphs.Add(image)
 
        ' Save output PDF document
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* فئة [BaseParagraph](../baseparagraph/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)