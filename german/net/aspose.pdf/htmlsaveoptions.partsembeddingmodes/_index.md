---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes Enum. Dieses Enum enumeriert mögliche Modi zum Einbetten von in HTML referenzierten Dateien. Es ermöglicht die Kontrolle darüber, ob referenzierte Dateien in die Haupt-HTML-Datei eingebettet oder als separate binäre Entitäten generiert werden.
type: docs
weight: 5710
url: /de/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes Enumeration

Dieses Enum enumeriert mögliche Modi zum Einbetten von in HTML referenzierten Dateien. Es ermöglicht die Kontrolle darüber, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS) in die Haupt-HTML-Datei eingebettet oder als separate binäre Entitäten generiert werden.

```csharp
public enum PartsEmbeddingModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Erzwingt das Einbetten aller referenzierten Dateien (CSS, Bilder, Schriftarten) in den generierten HTML-Markup (d.h. in das HTML selbst). Dieser Ansatz erzeugt eine HTML-Datei, aber die Gesamtgröße des Outputs wird größer (da Base64-Codierung von Binärdateien verwendet wird) und nicht alle Browser (insbesondere ältere) verarbeiten erfolgreich in HTML eingebettete Binärdateien. Aber es ermöglicht, HTML zu erhalten, das das gesamte Ergebnis enthält, ohne zusätzliche Dateien. |
| EmbedCssOnly | `1` | Erzwingt das Separieren aller referenzierten Dateien außer CSS (Bilder und Schriftarten). D.h. CSS wird in das resultierende HTML eingebettet, und alle anderen referenzierten Dateien (Bilder und Schriftarten) werden als externe Teile verarbeitet. Es generiert HTML, das für eine breite Palette von Browsern geeignet ist. |
| NoEmbedding | `2` | Erzwingt das Separieren referenzierter Dateien (CSS, Bilder, Schriftarten). Dieser Ansatz erzeugt eine Menge von Dateien, aber die Gesamtgröße des Outputs wird kleiner (da keine Base64-Codierung von Binärdateien verwendet wird). Auch dieser Ansatz generiert HTML, das für eine breite Palette von Browsern geeignet ist. |

### Siehe auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)