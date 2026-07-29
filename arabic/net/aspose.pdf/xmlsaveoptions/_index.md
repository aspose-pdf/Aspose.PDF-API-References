---
title: "Class XmlSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.XmlSaveOptions class. Save options for export to Xml format"
type: docs
weight: 11590
url: /ar/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق XML.

```csharp
public class XmlSaveOptions : SaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## أمثلة

The following example shows how to convert PDF file to XML file

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// The path to output XML File.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Initialize XmlSaveOptions\t
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Save XML file
		pdfDocument.Save(xmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf")

    ' The path to output XML File.
    Dim xmlFile = Path.Combine(dataDir, "PDF-to-XML.xml")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XmlSaveOptions
        Dim saveOptions As XmlSaveOptions = New XmlSaveOptions()
 
        ' Save XML file
        pdfDocument.Save(xmlFile, saveOptions)
    End Using
```

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


