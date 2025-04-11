---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Indique si plus de textes peuvent être obtenus ou non
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## Méthode PdfExtractor.HasNextPageText

Indique si plus de textes peuvent être obtenus ou non.

```csharp
public bool HasNextPageText()
```

### Valeur de retour

Peut obtenir plus de textes ou non, vrai signifie que c'est possible, ou faux.

## Exemples

L'exemple démontre l'utilisation de la propriété `HasNextPageText` dans un scénario d'extraction de texte.

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

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)