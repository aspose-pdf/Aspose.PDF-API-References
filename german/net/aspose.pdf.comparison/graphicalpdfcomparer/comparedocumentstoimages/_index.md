---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer-Methode. Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in Bildern abgelegt.
type: docs
weight: 50
url: /de/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages-Methode

Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in Bildern abgelegt.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Das erste Dokument, das verglichen werden soll. |
| document2 | Document | Das zweite Dokument, das verglichen werden soll. |
| targetDirectory | String | Das Verzeichnis, in dem die Vergleichsergebnisse gespeichert werden. |
| fileNamePrefix | String | Das Namenspräfix für die Bilder. |
| imageFormat | ImageFormat | Das Bildformat zum Speichern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wenn die zu vergleichenden Seiten unterschiedliche Größen haben. Wenn targetDirectory null oder ein leerer String ist. Wenn fileNamePrefix null oder ein leerer String ist. |

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [GraphicalPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)