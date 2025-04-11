---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.HtmlLoadOptions. تمثل الخيارات لتحميل/استيراد ملف HTML إلى مستند PDF
type: docs
weight: 5530
url: /ar/net/aspose.pdf/htmlloadoptions/
---
## فئة HtmlLoadOptions

تمثل الخيارات لتحميل/استيراد ملف HTML إلى مستند PDF.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | ينشئ خيارات تحميل لتحويل HTML إلى مستند PDF مع مسار أساسي فارغ. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | ينشئ خيارات تحميل لتحويل HTML إلى مستند PDF مع مسار أساسي محدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | المسار/الرابط الأساسي لملف HTML. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تعطل الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | يحصل أو يحدد أنواع الوسائط الممكنة المستخدمة أثناء العرض. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | يحصل أو يحدد السمة التي تحدد الترميز المستخدم لهذا المستند في وقت التحليل. إذا كانت هذه السمة فارغة، سيتم تحديد الترميز من سمة مجموعة أحرف المستند. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | يحصل أو يحدد إدراج الخطوط في المستند الناتج |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | يحصل أو يحدد العلامة التي تحدد أن قواعد @page المعرفة في CSS ستتجاوز القيم المعرفة في PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | يحصل أو يحدد عرض المستند بالكامل في صفحة واحدة |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | يحصل أو يحدد معلومات صفحة المستند |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | يحصل أو يحدد خيار التخطيط. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | أحيانًا يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة، يكون الوصول المباشر إلى الملفات المرجعية مستحيلًا: في هذه الحالة يجب استخدام بعض التعليمات البرمجية المخصصة الموضوعة في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه السمة. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | إذا كان تحميل البيانات الخارجية المشار إليها في HTML يتطلب بيانات اعتماد، يمكنك وضعها في هذه المعلمة - سيتم استخدامها أثناء تحميل الموارد الخارجية |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف HTML إلى ملف PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* فئة [LoadOptions](../loadoptions/)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)