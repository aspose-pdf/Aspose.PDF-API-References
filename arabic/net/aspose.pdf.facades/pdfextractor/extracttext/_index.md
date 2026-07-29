---
title: "PdfExtractor.ExtractText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. تستخرج النص من مستند Pdf باستخدام ترميز Unicode"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

يستخرج النص من مستند PDF باستخدام ترميز Unicode.

```csharp
public void ExtractText()
```

## أمثلة

يوضح المثال الأول كيفية استخراج كل النص من ملف PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText()
extractor.GetText("D:\Text\text.txt")
```

يوضح المثال الثاني كيفية استخراج نص كل صفحة إلى ملف txt واحد.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText();
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
extractor.ExtractText()
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

## ExtractText(Encoding) {#extracttext_1}

يستخرج النص من مستند PDF باستخدام الترميز المحدد.

```csharp
public void ExtractText(Encoding encoding)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| encoding | الترميز | ترميز النص المستخرج. |

## أمثلة

يوضح المثال الأول كيفية استخراج كل النص من ملف PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText(Encoding.Unicode);
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText(Encoding.Unicode)
extractor.GetText("D:\Text\text.txt")
```

يوضح المثال الثاني كيفية استخراج نص كل صفحة إلى ملف txt واحد.

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


