---
title: PdfExtractor.ExtractText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Extrai texto de um documento Pdf usando codificação Unicode
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

Extrai texto de um documento Pdf usando codificação Unicode.

```csharp
public void ExtractText()
```

## Exemplos

O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF.

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

O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt.

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

Extrai texto de um documento Pdf usando a codificação especificada.

```csharp
public void ExtractText(Encoding encoding)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encoding | Encoding | A codificação do texto extraído. |

## Exemplos

O primeiro exemplo demonstra como extrair todo o texto de um arquivo PDF.

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

O segundo exemplo demonstra como extrair o texto de cada página em um único arquivo txt.

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)