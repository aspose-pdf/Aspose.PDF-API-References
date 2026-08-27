---
title: "PdfExtractor.GetNextPageText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfExtractor-metod. Sparar en sidas text till fil"
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

Sparar en sidas text till en fil.

```csharp
public void GetNextPageText(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara texten. |

## Exempel

Exemplet demonstrerar användning av GetNextPageText-metoden i ett scenario för textutdragning.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

Sparar en sidas text till en ström.

```csharp
public void GetNextPageText(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara texten. |

## Exempel

Exemplet demonstrerar `GetNextPageText`-metodens användning i ett scenario för textutdragning.

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

### Se även

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


