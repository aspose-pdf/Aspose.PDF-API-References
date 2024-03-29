---
title: GetNextPageText
second_title: Aspose.PDF لمرجع .NET API
description: يحفظ نص صفحة واحدة في ملف.
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

يحفظ نص صفحة واحدة في ملف.

```csharp
public void GetNextPageText(string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمه لحفظ النص. |

### أمثلة

يوضح المثال استخدام أسلوب GetNextPageText في سيناريو استخراج النص.

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

---

## GetNextPageText(Stream) {#getnextpagetext}

يحفظ نص صفحة واحدة للدفق.

```csharp
public void GetNextPageText(Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ النص. |

### أمثلة

يوضح المثال ملف[`GetNextPageText`](../getnextpagetext) استخدام الطريقة في سيناريو استخراج النص.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### أنظر أيضا

* class [PdfExtractor](../../pdfextractor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfextractor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
