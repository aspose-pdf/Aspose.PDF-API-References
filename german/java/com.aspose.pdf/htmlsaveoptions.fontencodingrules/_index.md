---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Aufzählung definiert Regeln, die die Kodierungslogik anpassen."
type: docs
weight: 2050
url: /de/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Diese Aufzählung definiert Regeln, die die Kodierungslogik anpassen.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode ist ein spezieller Mechanismus, der dabei hilft, Eingabecodes in Unicode‑Symbole zu dekodieren. Laut Spezifikation muss er als erster aller Mechanismen verwendet werden, um Unicode‑Symbole für einen bestimmten Eingabecode zu erhalten. Allerdings enthalten einige Dokumente nicht‑standardisierte Schriften, und um diese Dokumente korrekt zu konvertieren, kann es notwendig sein, die Priorität von ToUnicode zu verringern und andere Mechanismen zum Dekodieren von Eingabecodes zu verwenden. |
| [Default](#Default) | Lassen Sie die Kodierungslogik "wie sie ist" – gemäß PDF‑Spezifikation. |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode ist ein spezieller Mechanismus, der dabei hilft, Eingabecodes in Unicode‑Symbole zu dekodieren. Laut Spezifikation muss er als erster aller Mechanismen verwendet werden, um Unicode‑Symbole für einen bestimmten Eingabecode zu erhalten. Allerdings enthalten einige Dokumente nicht‑standardisierte Schriften, und um diese Dokumente korrekt zu konvertieren, kann es notwendig sein, die Priorität von ToUnicode zu verringern und andere Mechanismen zum Dekodieren von Eingabecodes zu verwenden.

### Default {#Default}
```
public static final byte Default
```

Lassen Sie die Kodierungslogik "wie sie ist" – gemäß PDF‑Spezifikation.
