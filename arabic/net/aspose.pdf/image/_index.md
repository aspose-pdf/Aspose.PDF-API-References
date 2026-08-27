---
title: "الفئة Image"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Image. تمثل صورة."
type: docs
weight: 5990
url: /ar/net/aspose.pdf/image/
---
## Image class

يمثل الصورة.

```csharp
public sealed class Image : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Image](image/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapInfo](../../aspose.pdf/image/bitmapinfo/) { get; set; } | يحصل أو يعيّن بايتات الصورة غير المضغوطة. |
| [BitmapSize](../../aspose.pdf/image/bitmapsize/) { get; } | يحصل على حجم صورة البت ماب. |
| [File](../../aspose.pdf/image/file/) { get; set; } | يحصل أو يعيّن ملف الصورة. |
| [FileType](../../aspose.pdf/image/filetype/) { get; set; } | يحصل أو يعيّن نوع ملف الصورة. |
| [FixHeight](../../aspose.pdf/image/fixheight/) { get; set; } | يحصل أو يعيّن ارتفاع الصورة. |
| [FixWidth](../../aspose.pdf/image/fixwidth/) { get; set; } | يحصل أو يعيّن عرض الصورة. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية للفقرة |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [ImageScale](../../aspose.pdf/image/imagescale/) { get; set; } | يحصل أو يعيّن مقياس الصورة. |
| [ImageStream](../../aspose.pdf/image/imagestream/) { get; set; } | يحصل أو يعيّن تدفق الصورة. |
| [IsApplyResolution](../../aspose.pdf/image/isapplyresolution/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء. |
| [IsBlackWhite](../../aspose.pdf/image/isblackwhite/) { get; set; } | يحصل أو يعيّن قيمة من نوع bool تشير إلى ما إذا كان يتم إجبار الصورة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من تنسيق فرعي CCITT، يجب تعيين هذه الخاصية إلى true. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Title](../../aspose.pdf/image/title/) { get; set; } | يحصل أو يعيّن قيمة من نوع string تشير إلى عنوان الصورة. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/image/clone/)() | استنساخ الصورة. |
| static [GetMimeType](../../aspose.pdf/image/getmimetype/)(Image) | يعيد نوع mime للصورة. |

## أمثلة

المثال التالي يوضح كيفية تحويل الصور (PNG، JPEG، GIF، BMP، أو صيغ صور أخرى) إلى ملف PDF.

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// المسار إلى صورتك (bmp، png، gif، jpeg، إلخ) الملف.
	string imageFile = Path.Combine(dataDir, "Image-to-PDF.png");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "Image-to-PDF.pdf");

	//تهيئة مستند PDF فارغ
	using(Document pdfDocument = new Document()) 
	{
	  pdfDocument.Pages.Add();
	  Image image = new Image();

	  // تحميل ملف صورة تجريبي
	  image.File = imageFile;
	  pdfDocument.Pages[1].Paragraphs.Add(image);

	  // حفظ مستند PDF الناتج
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

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


