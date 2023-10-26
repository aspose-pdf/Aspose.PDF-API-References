---
title: PdfExtractor.GetNextPageText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Saves one pages text to file
type: docs
weight: 180
url: /net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

Saves one page's text to file.

```csharp
public void GetNextPageText(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file path and name to save the text. |

## Examples

The example demonstratres the GetNextPageText method usage in text extraction scenario.

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

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

Saves one page's text to stream.

```csharp
public void GetNextPageText(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the text. |

## Examples

The example demonstratres the `GetNextPageText` method usage in text extraction scenario.

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

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


