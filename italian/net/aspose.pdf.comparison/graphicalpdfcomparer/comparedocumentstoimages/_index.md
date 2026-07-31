---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo GraphicalPdfComparer. Confronta i documenti graficamente. Il risultato del confronto è collocato in immagini"
type: docs
weight: 50
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

Confronta i documenti graficamente. Il risultato del confronto è inserito nelle immagini.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Il primo documento da confrontare. |
| document2 | Document | Il secondo documento da confrontare. |
| targetDirectory | String | La directory in cui salvare i risultati del confronto. |
| fileNamePrefix | String | Il prefisso del nome delle immagini. |
| imageFormat | ImageFormat | Il formato immagine da salvare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Se le pagine confrontate hanno dimensioni diverse. Se targetDirectory è null o stringa vuota. Se fileNamePrefix è null o stringa vuota. |

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


