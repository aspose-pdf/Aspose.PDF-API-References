---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: ParagraphAbsorber-Eigenschaft. Ruft den Wert ab oder legt ihn fest, der angibt, wie oft aufeinanderfolgende Suchen nach feineren Elementen der Struktur durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Suchen nach horizontal geteilten Abschnitten und drei Suchen nach vertikal geteilten.
type: docs
weight: 50
url: /de/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth-Eigenschaft

Ruft den Wert ab oder legt ihn fest, der angibt, wie oft aufeinanderfolgende Suchen nach feineren Elementen der Struktur durchgeführt werden. Die standardmäßige Suchtiefe beträgt 3. Das bedeutet drei Suchen nach horizontal geteilten Abschnitten (Überschriften, Absätze usw.) und drei Suchen nach vertikal geteilten (Spalten).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Bemerkungen

Eine Erhöhung dieses Wertes kann zu einer geringfügigen Verringerung der Leistung führen, ohne sichtbare Änderungen im Suchergebnis. Eine Verringerung dieses Wertes kann zu einer falschen Bestimmung von Absätzen in Abschnitten führen. Wir empfehlen nicht, einen Wert unter dem Standard festzulegen, wenn Sie nicht nur 'grobe' Elemente der Seitenstruktur erhalten möchten.

### Siehe auch

* Klasse [ParagraphAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)