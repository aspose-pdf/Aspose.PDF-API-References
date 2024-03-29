---
title: ExtractText
second_title: Aspose.PDF für .NET-API-Referenz
description: Extrahiert Text aus einem PDF-Dokument mit Unicode-Codierung.
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

Extrahiert Text aus einem PDF-Dokument mit Unicode-Codierung.

```csharp
public void ExtractText()
```

### Beispiele

Das erste Beispiel zeigt, wie der gesamte Text aus einer PDF-Datei extrahiert wird. Das zweite Beispiel zeigt, wie der Text jeder Seite in eine TXT-Datei extrahiert wird.

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

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

Extrahiert Text aus einem PDF-Dokument unter Verwendung der angegebenen Kodierung.

```csharp
public void ExtractText(Encoding encoding)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoding | Encoding | Die Kodierung des extrahierten Textes. |

### Beispiele

Das erste Beispiel zeigt, wie der gesamte Text aus einer PDF-Datei extrahiert wird. Das zweite Beispiel zeigt, wie der Text jeder Seite in eine TXT-Datei extrahiert wird.

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

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
