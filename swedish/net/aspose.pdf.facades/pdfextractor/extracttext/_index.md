---
title: PdfExtractor.ExtractText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-metod. Extraherar text från ett Pdf-dokument med hjälp av Unicode-kodning
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

Extraherar text från ett Pdf-dokument med hjälp av Unicode-kodning.

```csharp
public void ExtractText()
```

## Exempel

Det första exemplet visar hur man extraherar all text från en PDF-fil.

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

Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil.

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

Extraherar text från ett Pdf-dokument med angiven kodning.

```csharp
public void ExtractText(Encoding encoding)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoding | Encoding | Kodningen av den extraherade texten. |

## Exempel

Det första exemplet visar hur man extraherar all text från en PDF-fil.

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

Det andra exemplet visar hur man extraherar varje sidas text till en txt-fil.

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)