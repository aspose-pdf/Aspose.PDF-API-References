---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Dieses Enum beschreibt mögliche Antialiasing‑Maßnahmen während der Konvertierung"
type: docs
weight: 2000
url: /de/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Dieses Enum beschreibt mögliche Antialiasing‑Maßnahmen während der Konvertierung

## Felder

| Feld | Beschreibung |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Keine spezielle Antialiasing-Verarbeitung wird verwendet. Dies ist eine optimale Option für die überwiegende Mehrheit der Dokumente und erfordert keine zusätzliche Zeit während der Konvertierung. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | In einem solchen Fall versucht der Konverter, Stellen mit benachbarten grafischen Hintergrundelementen zu erkennen und das resultierende HTML entsprechend zu korrigieren. Diese Option ermöglicht die Verbesserung des Exportergebnisses für Dokumente, die Hintergründe aus mehreren benachbarten grafischen Elementen enthalten (für solche Dokumente versuchen PDF‑Renderer, z. B. Acrobat Reader, normalerweise glatte Grenzen der Elemente während des Renderns. Mit dieser Option imitiert der Konverter dieses Verhalten von PDF‑Renderern). Diese Option ermöglicht die Verbesserung des Layouts des Exportergebnisses für einige spezifische Dokumente (die solche zusammengesetzten Hintergründe verwenden), erfordert jedoch zusätzliche Zeit für die Verarbeitung (in der Regel etwa 10‑15 % zusätzliche Zeit). Die Verwendung dieses Modus im allgemeinen Fall wird daher nicht empfohlen. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Keine spezielle Antialiasing-Verarbeitung wird verwendet. Dies ist eine optimale Option für die überwiegende Mehrheit der Dokumente und erfordert keine zusätzliche Zeit während der Konvertierung.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

In einem solchen Fall versucht der Konverter, Stellen mit benachbarten grafischen Hintergrundelementen zu erkennen und das resultierende HTML entsprechend zu korrigieren. Diese Option ermöglicht die Verbesserung des Exportergebnisses für Dokumente, die Hintergründe aus mehreren benachbarten grafischen Elementen enthalten (für solche Dokumente versuchen PDF‑Renderer, z. B. Acrobat Reader, normalerweise glatte Grenzen der Elemente während des Renderns. Mit dieser Option imitiert der Konverter dieses Verhalten von PDF‑Renderern). Diese Option ermöglicht die Verbesserung des Layouts des Exportergebnisses für einige spezifische Dokumente (die solche zusammengesetzten Hintergründe verwenden), erfordert jedoch zusätzliche Zeit für die Verarbeitung (in der Regel etwa 10‑15 % zusätzliche Zeit). Die Verwendung dieses Modus im allgemeinen Fall wird daher nicht empfohlen.
