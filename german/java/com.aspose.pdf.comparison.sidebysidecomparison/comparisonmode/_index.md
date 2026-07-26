---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Die Aufzählung der Vergleichsmodi."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

Die Aufzählung der Vergleichsmodi.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Alle Leerzeichen werden ignoriert. Änderungen werden nur in Wörtern gesucht. |
| [Normal](#Normal) | Normaler Modus. Nur Leerzeichen innerhalb von Textfragmenten werden berücksichtigt (abhängig davon, wie das Dokument erzeugt wird). |
| [ParseSpaces](#ParseSpaces) | Der Modus ist dem normalen ähnlich, versucht jedoch, den visuellen Abstand zwischen Textfragmenten basierend auf der Distanz zu berücksichtigen. Die Erkennung der Anzahl von Leerzeichen zwischen Fragmenten kann ungenau sein, da dies stark davon abhängt, wie die Dokumente erzeugt werden. Wenn Dokumente von verschiedenen Generatoren erstellt werden, kann es Ungenauigkeiten beim Vergleich von Leerzeichen zwischen Textfragmenten geben. Diese Option kann Ergebnisse liefern, die zwar logisch sind, aber von den erwarteten Vergleichsergebnissen abweichen, wenn sie auf komplex strukturierten Dokumenten angewendet wird. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Alle Leerzeichen werden ignoriert. Änderungen werden nur in Wörtern gesucht.

### Normal {#Normal}
```
public static final int Normal
```

Normaler Modus. Nur Leerzeichen innerhalb von Textfragmenten werden berücksichtigt (abhängig davon, wie das Dokument erzeugt wird).

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

Der Modus ist dem normalen ähnlich, versucht jedoch, den visuellen Abstand zwischen Textfragmenten basierend auf der Distanz zu berücksichtigen. Die Erkennung der Anzahl von Leerzeichen zwischen Fragmenten kann ungenau sein, da dies stark davon abhängt, wie die Dokumente erzeugt werden. Wenn Dokumente von verschiedenen Generatoren erstellt werden, kann es Ungenauigkeiten beim Vergleich von Leerzeichen zwischen Textfragmenten geben. Diese Option kann Ergebnisse liefern, die zwar logisch sind, aber von den erwarteten Vergleichsergebnissen abweichen, wenn sie auf komplex strukturierten Dokumenten angewendet wird.
