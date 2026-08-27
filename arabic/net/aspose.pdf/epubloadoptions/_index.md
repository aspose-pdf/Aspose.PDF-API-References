---
title: "الفئة EpubLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.EpubLoadOptions. تحتوي على خيارات لتحميل/استيراد ملف EPUB إلى مستند pdf"
type: docs
weight: 4170
url: /ar/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

يحتوي على خيارات تحميل/استيراد ملف EPUB إلى مستند PDF.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | ينشئ خيارات التحميل الافتراضية لتحويل ملف EPUB إلى مستند pdf. حجم صفحة pdf الافتراضي - A4 300dpi 2480 × 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | ينشئ خيارات التحميل بحجم صفحة محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | يحصل أو يعيّن الـ Css المخصص لتطبيقه عند فتح مستند Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | يحصل على مرجع إلى كائن يمثل معلومات الهوامش. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | يحصل أو يعيّن حجم صفحة الإخراج للاستيراد. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | يمثل وضع استخدام مساحة الهوامش - يحدد معالجة التعليمات (إن وجدت) في CSS للمستند المستورد المتعلقة باستخدام الهوامش. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | تنبيه! تم تنفيذ الميزة ولكن لم تُضف بعد إلى API العامة بسبب مشكلة عائق في طبقة OSHARED تم اكتشافها في المستند النموذجي. يمثل وضع استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML, EPUB إلخ) عادةً ما تكون ذات تصميم مرن، لذا يسمح بتلائم حجم الصفحة المطلوب. لكن أحيانًا يكون للمحتوى مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى داخل حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب في مستند PDF الناتج). |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف EPUB إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف EPUB الخاص بك.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// تهيئة EpubLoadOptions
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// حفظ ملف PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


