---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Wenn die SplitToPages-Eigenschaft von HtmlSaveOptions gesetzt ist, werden während der Konvertierung von PDF zu HTML mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Klasse stellt eine Menge von."
type: docs
weight: 2100
url: /de/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Wenn die Eigenschaft SplitToPages von HtmlSaveOptions gesetzt ist, werden während der Konvertierung von PDF zu HTML mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Klasse repräsentiert einen Datensatz, der sich auf das benutzerdefinierte Speichern des Markups einer HTML-Seite während der PDF-zu-HTML-Konvertierung bezieht.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getContentStream](#getContentStream--) | Vom Konverter festgelegt. Stellt das gespeicherte HTML als Stream dar. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft enthält die Ordnungszahl der gespeicherten HTML‑Seitendatei. Die Eigenschaft kann in der Logik von benutzerdefiniertem Code verwendet werden, um zu entscheiden, wie oder wo die HTML‑Seite gespeichert wird, und wenn das Aufteilen nach Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine große HTML‑Seite für das gesamte Quell‑Dokument erzeugt wird. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft teilt dem benutzerdefinierten Code mit, von welcher Seite des ursprünglichen PDFs das gespeicherte HTML‑Markup erstellt wurde. Wenn die Originalseitennummer aus irgendeinem Grund unbekannt ist oder SplitToPages=false, enthält diese Eigenschaft immer '0', was signalisiert, dass der Konverter die genaue Original‑PDF‑Seitenzahl für die bereitgestellte HTML‑Markup‑Datei nicht liefern kann. |
| [getSupposedFileName](#getSupposedFileName--) | Vom Konverter festgelegt. Angenommener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie verarbeitet wird oder wo der Inhalt gespeichert wird. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Sollte im benutzerdefinierten Code gesetzt werden, wenn nötig. Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus irgendeinem Grund das bereitgestellte HTML-Markup nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst in der standardmäßigen Weise des Konverters verarbeitet werden soll. Das Setzen dieses Flags im benutzerdefinierten Code bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Vom Konverter festgelegt. Stellt das gespeicherte HTML als Stream dar. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Sollte im benutzerdefinierten Code gesetzt werden, wenn nötig. Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus irgendeinem Grund das bereitgestellte HTML-Markup nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst in der standardmäßigen Weise des Konverters verarbeitet werden soll. Das Setzen dieses Flags im benutzerdefinierten Code bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft enthält die Ordnungszahl der gespeicherten HTML‑Seitendatei. Die Eigenschaft kann in der Logik von benutzerdefiniertem Code verwendet werden, um zu entscheiden, wie oder wo die HTML‑Seite gespeichert wird, und wenn das Aufteilen nach Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine große HTML‑Seite für das gesamte Quell‑Dokument erzeugt wird. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft teilt dem benutzerdefinierten Code mit, von welcher Seite des ursprünglichen PDFs das gespeicherte HTML‑Markup erstellt wurde. Wenn die Originalseitennummer aus irgendeinem Grund unbekannt ist oder SplitToPages=false, enthält diese Eigenschaft immer '0', was signalisiert, dass der Konverter die genaue Original‑PDF‑Seitenzahl für die bereitgestellte HTML‑Markup‑Datei nicht liefern kann. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Vom Konverter festgelegt. Angenommener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie verarbeitet wird oder wo der Inhalt gespeichert wird. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Vom Konverter festgelegt. Stellt das gespeicherte HTML als Stream dar.

**Returns:**
InputStream-Instanz

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft enthält die Ordnungszahl der gespeicherten HTML‑Seitendatei. Die Eigenschaft kann in der Logik von benutzerdefiniertem Code verwendet werden, um zu entscheiden, wie oder wo die HTML‑Seite gespeichert wird, und wenn das Aufteilen nach Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine große HTML‑Seite für das gesamte Quell‑Dokument erzeugt wird.

**Returns:**
int-Wert

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft teilt dem benutzerdefinierten Code mit, von welcher Seite des ursprünglichen PDFs das gespeicherte HTML‑Markup erstellt wurde. Wenn die Originalseitennummer aus irgendeinem Grund unbekannt ist oder SplitToPages=false, enthält diese Eigenschaft immer '0', was signalisiert, dass der Konverter die genaue Original‑PDF‑Seitenzahl für die bereitgestellte HTML‑Markup‑Datei nicht liefern kann.

**Returns:**
int-Wert

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Vom Konverter festgelegt. Angenommener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie verarbeitet wird oder wo der Inhalt gespeichert wird.

**Returns:**
String Wert

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Sollte im benutzerdefinierten Code gesetzt werden, wenn nötig. Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus irgendeinem Grund das bereitgestellte HTML-Markup nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst in der standardmäßigen Weise des Konverters verarbeitet werden soll. Das Setzen dieses Flags im benutzerdefinierten Code bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss.

**Returns:**
boolescher Wert

### setContentStream {#setContentStream-java.io.InputStream-}
Vom Konverter festgelegt. Stellt das gespeicherte HTML als Stream dar.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Sollte im benutzerdefinierten Code gesetzt werden, wenn nötig. Dieses Flag muss im benutzerdefinierten Code auf "true" gesetzt werden, wenn aus irgendeinem Grund das bereitgestellte HTML-Markup nicht mit benutzerdefiniertem Code, sondern mit dem Code des Konverters selbst in der standardmäßigen Weise des Konverters verarbeitet werden soll. Das Setzen dieses Flags im benutzerdefinierten Code bedeutet also, dass der benutzerdefinierte Code die referenzierte Datei nicht verarbeitet hat und der Konverter sie selbst übernehmen muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| customProcessingCancelled |  | boolescher Wert |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft enthält die Ordnungszahl der gespeicherten HTML‑Seitendatei. Die Eigenschaft kann in der Logik von benutzerdefiniertem Code verwendet werden, um zu entscheiden, wie oder wo die HTML‑Seite gespeichert wird, und wenn das Aufteilen nach Seiten deaktiviert ist, enthält dieser Wert immer '1', da in diesem Fall nur eine große HTML‑Seite für das gesamte Quell‑Dokument erzeugt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlHostPageNumber |  | int-Wert |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Vom Konverter festgelegt. Wenn die SplitToPages‑Eigenschaft gesetzt ist, werden während der Konvertierung mehrere HTML-Dateien (eine HTML-Datei pro konvertierter Seite) erstellt. Diese Eigenschaft teilt dem benutzerdefinierten Code mit, von welcher Seite des ursprünglichen PDFs das gespeicherte HTML‑Markup erstellt wurde. Wenn die Originalseitennummer aus irgendeinem Grund unbekannt ist oder SplitToPages=false, enthält diese Eigenschaft immer '0', was signalisiert, dass der Konverter die genaue Original‑PDF‑Seitenzahl für die bereitgestellte HTML‑Markup‑Datei nicht liefern kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfHostPageNumber |  | int-Wert |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Vom Konverter festgelegt. Angenommener Dateiname, der vom Konverter zum Code der benutzerdefinierten Methode übergeht. Kann im benutzerdefinierten Code verwendet werden, um zu entscheiden, wie verarbeitet wird oder wo der Inhalt gespeichert wird.
