---
title: HasNextPageText
second_title: Aspose.PDF لمرجع .NET API
description: يشير إلى إمكانية الحصول على المزيد من النصوص أم لا.
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## PdfExtractor.HasNextPageText method

يشير إلى إمكانية الحصول على المزيد من النصوص أم لا.

```csharp
public bool HasNextPageText()
```

### قيمة الإرجاع

يمكن الحصول على المزيد من النصوص أو لا ، صحيح هو يمكن ، أو خطأ.

### أمثلة

يوضح المثال ملف`HasNextPageText` استخدام الخاصية في سيناريو استخراج النص.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### أنظر أيضا

* class [PdfExtractor](../../pdfextractor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfextractor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
