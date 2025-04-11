---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. تشير إلى ما إذا كان يمكن الحصول على المزيد من النصوص أم لا
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## طريقة PdfExtractor.HasNextPageText

تشير إلى ما إذا كان يمكن الحصول على المزيد من النصوص أم لا.

```csharp
public bool HasNextPageText()
```

### قيمة الإرجاع

يمكن الحصول على المزيد من النصوص أم لا، true تعني يمكن، أو false.

## أمثلة

توضح المثال استخدام خاصية `HasNextPageText` في سيناريو استخراج النص.

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

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)