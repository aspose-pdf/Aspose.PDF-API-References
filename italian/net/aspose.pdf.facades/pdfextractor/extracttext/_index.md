---
title: PdfExtractor.ExtractText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Extracts text from a Pdf document using Unicode encoding
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfextractor/extracttext/
---
title: PdfExtractor.ExtractText  
second_title: Aspose.PDF for .NET API Reference  
description: Metodo PdfExtractor. Estrae il testo da un documento PDF utilizzando codifica Unicode  
type: docs  
weight: 130  
url: /net/aspose.pdf.facades/pdfextractor/extracttext/  

## ExtractText() {#extracttext}  

Estrae il testo da un documento PDF utilizzando codifica Unicode.  

```csharp
public void ExtractText()
```  

## Esempi  

Primo esempio dimostra come estrarre tutto il testo da un file PDF.  

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

Secondo esempio dimostra come estrarre il testo di ogni pagina in un file txt.  

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

### Vedi anche  

* classe [PdfExtractor](../)  
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)  
* assembly [Aspose.PDF](../../../)  

 | --- | --- |  
| encoding | Encoding | La codifica del testo estratto. |  

## Esempi  

Primo esempio dimostra come estrarre tutto il testo da un file PDF.  

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

Secondo esempio dimostra come estrarre il testo di ogni pagina in un file txt.  

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

### Vedi anche  

* classe [PdfExtractor](../)  
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)  
* assembly [Aspose.PDF](../../../)