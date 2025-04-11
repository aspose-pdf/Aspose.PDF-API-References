---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType Enum. Dieses Enum beschreibt mögliche Antialiasing-Maßnahmen während der Konvertierung
type: docs
weight: 5570
url: /de/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType Enumeration

Dieses Enum beschreibt mögliche Antialiasing-Maßnahmen während der Konvertierung

```csharp
public enum AntialiasingProcessingType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | keine spezielle Antialiasing-Verarbeitung in Verwendung. Dies ist eine optimale Option für die überwältigende Mehrheit der Dokumente und erfordert keine zusätzliche Zeit während der Konvertierung |
| TryCorrectResultHtml | `1` | In diesem Fall versucht der Konverter, Stellen mit angrenzenden grafischen Elementen im Hintergrund zu erkennen und das Ergebnis-HTML entsprechend zu korrigieren. Diese Option ermöglicht es, das Ergebnis des Exports für Dokumente zu verbessern, die Hintergründe enthalten, die aus mehreren angrenzenden grafischen Elementen bestehen (für solche Dokumente versuchen PDF-Renderer, z. B. Acrobat Reader, normalerweise, die Grenzen der Elemente während des Renderns zu glätten. Mit dieser Option ahmt der Konverter dieses Verhalten von PDF-Renderern nach. Diese Option ermöglicht es, das Layout des Ergebnisses des Exports für einige spezifische Dokumente (die solche zusammengesetzten Hintergründe verwenden) zu verbessern, erfordert jedoch zusätzliche Zeit für die Verarbeitung (normalerweise etwa 10-15% zusätzliche Zeit). Daher wird die Verwendung dieses Modus im Allgemeinen nicht empfohlen. |

### Siehe auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)