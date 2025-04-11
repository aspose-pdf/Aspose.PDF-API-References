---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer metodo. Compara documenti graficamente. Il risultato della comparazione viene visualizzato all'interno delle immagini.
type: docs
weight: 50
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Metodo GraphicalPdfComparer.CompareDocumentsToImages

Confronta documenti graficamente. Il risultato del confronto è posizionato nelle immagini.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Il primo documento da confrontare. |
| document2 | Document | Il secondo documento da confrontare. |
| targetDirectory | String | La directory per salvare i risultati del confronto. |
| fileNamePrefix | String | Il prefisso del nome delle immagini. |
| imageFormat | ImageFormat | Il formato dell'immagine da salvare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Se le pagine da confrontare sono di dimensioni diverse. Se targetDirectory è nullo o una stringa vuota. Se fileNamePrefix è nullo o una stringa vuota. |

### Vedi Anche

* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)