---
title: "الفئة XmlLoadOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.XmlLoadOptions. تمثل الخيارات لتحميل/استيراد ملف XML إلى مستند pdf"
type: docs
weight: 11580
url: /ar/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

يمثل خيارات تحميل/استيراد ملف XML إلى مستند pdf.

```csharp
public class XmlLoadOptions : LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | ينشئ كائن `XmlLoadOptions` بدون بيانات xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | ينشئ كائن `XmlLoadOptions` ببيانات xsl. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | ينشئ كائن `XmlLoadOptions` ببيانات xsl. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | يحصل أو يعيّن العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما تكون `true`، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بتضمين خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. القيمة الافتراضية هي `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | يمثل تنسيق الملف الذي تصفه [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | يحصل على بيانات xsl لتحويل xml إلى مستند pdf. |

## أمثلة

المثال التالي يوضح كيفية تحويل ملف XML إلى ملف PDF

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// المسار إلى ملف XML الخاص بك.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// المسار إلى ملف PDF الناتج.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// تهيئة XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### انظر أيضًا

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


