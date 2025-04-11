---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.EpubLoadOptions. تحتوي على خيارات لتحميل/استيراد ملف EPUB إلى مستند PDF
type: docs
weight: 4050
url: /ar/net/aspose.pdf/epubloadoptions/
---
## فئة EpubLoadOptions

تحتوي على خيارات لتحميل/استيراد ملف EPUB إلى مستند PDF.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | ينشئ خيارات تحميل افتراضية لتحويل ملف EPUB إلى مستند PDF. حجم صفحة PDF الافتراضي - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | ينشئ خيارات تحميل بحجم صفحة محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | يحصل أو يحدد Css مخصص للتطبيق عند فتح مستند Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | يحصل على مرجع على كائن يمثل معلومات الهوامش. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | يحصل أو يحدد حجم الصفحة الناتج للاستيراد. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | يمثل وضع استخدام منطقة الهوامش - يحدد معالجة التعليمات (إن وجدت) من CSS للمستند المستورد المتعلقة باستخدام الهوامش. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | انتباه! تم تنفيذ الميزة ولكن لم يتم وضعها بعد في واجهة برمجة التطبيقات العامة منذ ظهور مشكلة عائق في طبقة OSHARED للمستند النموذجي. يمثل وضع استخدام حجم الصفحة أثناء التحويل. عادةً ما تحتوي التنسيقات (مثل HTML، EPUB، إلخ) على تصميم عائم، لذا، يسمح بتناسب حجم الصفحة المطلوب. ولكن في بعض الأحيان يحتوي المحتوى على مواضع أفقية أو حجم محدد لا يسمح بوضع المحتوى في حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به في هذه الحالة (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب لمستند PDF الناتج). |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف EPUB إلى ملف PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
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

* فئة [LoadOptions](../loadoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)