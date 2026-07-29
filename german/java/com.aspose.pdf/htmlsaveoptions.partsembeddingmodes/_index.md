---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Dieses Enum enumeriert mögliche Einbettungsmodi von in HTML referenzierten Dateien. Es ermöglicht die Steuerung, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS-Dateien) in das Hauptdokument eingebettet werden."
type: docs
weight: 2130
url: /de/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Diese Aufzählung enumeriert mögliche Einbettungsmodi von in HTML referenzierten Dateien. Sie ermöglicht die Kontrolle, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS-Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binärobjekte erzeugt werden.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Erzwingt das Einbetten aller referenzierten Dateien (Css,Images,Fonts) in das erzeugte HTML-Markup (d. h. in das HTML selbst). Dieser Ansatz erzeugt eine HTML-Datei, aber die Gesamtausgabegröße wird größer (weil Base64‑Kodierung von Binärdateien verwendet wird) und nicht alle Browser (insbesondere ältere) verarbeiten eingebettete Binärdateien in HTML erfolgreich. Er ermöglicht jedoch das Erhalten von HTML, das das gesamte Ergebnis enthält, ohne zusätzliche Dateien. |
| [EmbedCssOnly](#EmbedCssOnly) | Erzwingt das Trennen aller referenzierten Dateien außer CSS (Images und Fonts). Das heißt, CSS wird in das Ergebnis‑HTML eingebettet, und alle anderen referenzierten Dateien (Images und Fonts) werden als externe Teile verarbeitet. Es erzeugt HTML, das für ein breites Spektrum an Browsern geeignet ist. |
| [NoEmbedding](#NoEmbedding) | Erzwingt das Trennen referenzierter Dateien (Css, Images, Fonts). Dieser Ansatz erzeugt eine Menge von Dateien, aber die Gesamtausgabegröße wird kleiner (weil keine Base64‑Kodierung von Binärdateien verwendet wird). Außerdem erzeugt ein solcher Ansatz HTML, das für ein breites Spektrum an Browsern geeignet ist. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Erzwingt das Einbetten aller referenzierten Dateien (Css,Images,Fonts) in das erzeugte HTML-Markup (d. h. in das HTML selbst). Dieser Ansatz erzeugt eine HTML-Datei, aber die Gesamtausgabegröße wird größer (weil Base64‑Kodierung von Binärdateien verwendet wird) und nicht alle Browser (insbesondere ältere) verarbeiten eingebettete Binärdateien in HTML erfolgreich. Er ermöglicht jedoch das Erhalten von HTML, das das gesamte Ergebnis enthält, ohne zusätzliche Dateien.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Erzwingt das Trennen aller referenzierten Dateien außer CSS (Images und Fonts). Das heißt, CSS wird in das Ergebnis‑HTML eingebettet, und alle anderen referenzierten Dateien (Images und Fonts) werden als externe Teile verarbeitet. Es erzeugt HTML, das für ein breites Spektrum an Browsern geeignet ist.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Erzwingt das Trennen referenzierter Dateien (Css, Images, Fonts). Dieser Ansatz erzeugt eine Menge von Dateien, aber die Gesamtausgabegröße wird kleiner (weil keine Base64‑Kodierung von Binärdateien verwendet wird). Außerdem erzeugt ein solcher Ansatz HTML, das für ein breites Spektrum an Browsern geeignet ist.
