---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode-Enum. Die Vergleichsmodus-Enumeration
type: docs
weight: 3140
url: /de/net/aspose.pdf.comparison/comparisonmode/
---
## Vergleichsmodus-Enumeration

Die Vergleichsmodus-Enumeration.

```csharp
public enum ComparisonMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Normal | `0` | Normalmodus. Nur Leerzeichen innerhalb von Textfragmenten werden berücksichtigt (abhängig davon, wie das Dokument erstellt wurde.) |
| IgnoreSpaces | `1` | Alle Leerzeichen werden ignoriert. Änderungen werden nur in Wörtern gesucht. |
| ParseSpaces | `2` | Der Modus ähnelt dem Normalmodus, versucht jedoch, den visuellen Abstand zwischen Textfragmenten basierend auf der Distanz zu berücksichtigen. Die Erkennung der Anzahl der Leerzeichen zwischen Fragmenten kann ungenau sein, da dies stark davon abhängt, wie die Dokumente erstellt werden. Wenn Dokumente von verschiedenen Generatoren erstellt werden, kann es Ungenauigkeiten beim Vergleich von Leerzeichen zwischen Textfragmenten geben. |

### Siehe auch

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)