---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.XslFoLoadOptions. تمثل خيارات تحميل/استيراد ملف XSLFO إلى مستند PDF
type: docs
weight: 11530
url: /ar/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

تمثل خيارات تحميل/استيراد ملف XSL-FO إلى مستند PDF.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | ينشئ كائن `XslFoLoadOptions` بدون بيانات XSL. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | ينشئ كائن `XslFoLoadOptions` مع بيانات XSL. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | ينشئ كائن `XslFoLoadOptions` مع بيانات XSL. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | المسار/الرابط الأساسي الذي يتم البحث منه عن المسارات النسبية للموارد الخارجية (إن وجدت) المشار إليها في ملف SVG المحمل. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يحدد علامة لتعطيل أي قيود ترخيص لجميع الخطوط أثناء تحميل الملف. عندما تكون القيمة `true`، يسمح بتنفيذ العمليات مع الخطوط التي يحظرها ترخيص هذا الخط، على سبيل المثال يسمح بإدراج خط في مستند PDF حتى لو كانت قواعد الترخيص تمنع الإدراج لهذا الخط. بشكل افتراضي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية التحميل. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | يحصل على بيانات XSL لتحويل XML إلى مستند PDF. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | قائمة XsltArgumentList لإدراج القيم في معلمات XLS الموجودة. يحتوي ملف XLS على معلمة 'animal' بدون قيمة: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); الآن يفترض المحول أن هناك معلمة 'animal' بقيمة 'cat' في ملف XLS. |

## Fields

| Name | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | يمكن أن يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يقوم هذا التعداد بإدراج الاستراتيجيات الممكنة للتعامل مع تلك الأخطاء. |

## Examples

يوضح المثال التالي كيفية تحويل ملف XSL-FO إلى ملف PDF

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
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

### See Also

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)