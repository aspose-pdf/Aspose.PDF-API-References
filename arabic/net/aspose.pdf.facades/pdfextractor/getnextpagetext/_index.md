---
title: "PdfExtractor.GetNextPageText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. تحفظ نص صفحة واحدة إلى ملف"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

يحفظ نص صفحة واحدة إلى ملف.

```csharp
public void GetNextPageText(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | مسار الملف واسمها لحفظ النص. |

## أمثلة

يوضح المثال استخدام طريقة GetNextPageText في سيناريو استخراج النص.

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

---

## GetNextPageText(Stream) {#getnextpagetext}

يحفظ نص صفحة واحدة إلى تدفق.

```csharp
public void GetNextPageText(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ النص. |

## أمثلة

يوضح المثال استخدام طريقة `GetNextPageText` في سيناريو استخراج النص.

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

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


