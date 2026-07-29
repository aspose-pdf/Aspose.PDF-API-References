---
title: "الفئة XslFoLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.XslFoLoadOptions. تمثل الخيارات لتحميل/استيراد ملف XSLFO إلى مستند pdf."
type: docs
weight: 11720
url: /ar/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

يمثل خيارات تحميل/استيراد ملف XSL-FO إلى مستند pdf.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | ينشئ كائن `XslFoLoadOptions` بدون بيانات xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | ينشئ كائن `XslFoLoadOptions` ببيانات xsl. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | ينشئ كائن `XslFoLoadOptions` ببيانات xsl. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | مسار/عنوان URL الأساسي الذي يتم البحث من خلاله عن المسارات النسبية للموارد الخارجية (إن وجدت) المشار إليها في ملف SVG المحمَّل. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | يحصل على بيانات xsl لتحويل xml إلى مستند pdf. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList لإدراج القيم في معلمات xls الموجودة  ملف XLS يحتوي على معلمة 'animal' بدون قيمة: XsltArgumentList args = new XsltArgumentList(); args.AddParam(\"animal\", \"\", \"cat\"); الآن يفترض المحول وجود معلمة 'animal' بالقيمة 'cat' في ملف XLS. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا التعداد الاستراتيجيات الممكنة للتعامل مع تلك الأخطاء. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف XSL-FO إلى ملف PDF.

```csharp
[C#]
// المسار إلى دليل المستندات.
string dataDir = @"YOUR_DATA_DIRECTORY";

// المسار إلى ملف XSL-FO الخاص بك.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// المسار إلى ملف PDF الناتج.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// تهيئة XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // حفظ ملف PDF
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


