---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer-Methode. Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem Bild platziert.
type: docs
weight: 70
url: /de/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage-Methode

Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem Bild platziert.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page1 | Seite | Die erste Seite, die verglichen werden soll. |
| page2 | Seite | Die zweite Seite, die verglichen werden soll. |
| resultImagePath | Zeichenfolge | Der Pfad zur Zieldatei des Bildes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wenn die zu vergleichenden Seiten unterschiedliche Größen haben. Wenn resultImagePath null oder eine leere Zeichenfolge ist. Es gibt ein unbekanntes Speicherformat für das Bild. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [GraphicalPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)