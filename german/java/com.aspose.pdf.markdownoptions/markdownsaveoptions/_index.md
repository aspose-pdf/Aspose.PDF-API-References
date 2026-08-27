---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Dokument‑Speicheroption‑Klasse im Markdown-Format dar."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Stellt die Dokument‑Speicheroption‑Klasse im Markdown-Format dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Erstellt eine Instanzoption zum Speichern eines Dokuments im Markdown-Format. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Lese oder setze einen rechteckigen Bereich, um Inhalt nach Markdown zu extrahieren. |
| [getEmphasisStyle](#getEmphasisStyle--) | Liest oder setzt den Hervorhebungsstil für das erzeugte Dokument. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Liest und setzt eine Eigenschaft, die angibt, ob Vektorgrafiken extrahiert werden sollen. |
| [getHeadingLevels](#getHeadingLevels--) | Definiert die erwarteten Überschriftenebenen, die in der FontSize-Erkennungs-Header-Strategie verwendet werden. Wenn dieser Eigenschaftswert gesetzt ist, wird die Header-Erkennungsstrategie {@link HeadingRecognitionStrategy#Heuristic} ausgewählt, wenn {@link HeadingRecognitionStrategy#Auto} Strategien gesetzt sind, selbst wenn das Dokument Lesezeichen enthält. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Liest oder setzt die Header-Erkennungsstrategie. |
| [getHeadingStyle](#getHeadingStyle--) | Liest oder setzt den Überschriftsstil für das erzeugte Dokument. |
| [getLineBreakStyle](#getLineBreakStyle--) | Liest oder setzt den Zeilenumbruchstil für das erzeugte Dokument. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Liest und setzt den Verzeichnisnamen, in dem Dokumentressourcen wie Bilder gespeichert werden. Wenn der Wert nicht angegeben ist, werden die Bilder in dasselbe Verzeichnis wie die Markdown-Datei selbst geschrieben. Dies ist kein Pfad, sondern nur ein Name! Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Liest und setzt den Verzeichnisnamen, um Dokumentressourcen wie Bilder zu speichern. Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Liest und setzt die Erlaubnis, Tief- und Hochstellungen zu konvertieren. Dieser Wert ist standardmäßig true. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Liest und setzt die Erlaubnis, ein img-Tag zu verwenden, um Bilder links und rechts vom Text einzufügen. In diesem Fall wird im Markdown-Viewer der Text um das Bild herumfließen. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Lese oder setze einen rechteckigen Bereich, um Inhalt nach Markdown zu extrahieren. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Liest oder setzt den Hervorhebungsstil für das erzeugte Dokument. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Liest und setzt eine Eigenschaft, die angibt, ob Vektorgrafiken extrahiert werden sollen. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Definiert die erwarteten Überschriftenebenen, die in der FontSize-Erkennungs-Header-Strategie verwendet werden. Wenn dieser Eigenschaftswert gesetzt ist, wird die Header-Erkennungsstrategie {@link HeadingRecognitionStrategy#Heuristic} ausgewählt, wenn {@link HeadingRecognitionStrategy#Auto} Strategien gesetzt sind, selbst wenn das Dokument Lesezeichen enthält. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Liest oder setzt die Header-Erkennungsstrategie. |
| [setHeadingStyle](#setHeadingStyle-int-) | Liest oder setzt den Überschriftsstil für das erzeugte Dokument. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Liest oder setzt den Zeilenumbruchstil für das erzeugte Dokument. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Liest und setzt den Verzeichnisnamen, in dem Dokumentressourcen wie Bilder gespeichert werden. Wenn der Wert nicht angegeben ist, werden die Bilder in dasselbe Verzeichnis wie die Markdown-Datei selbst geschrieben. Dies ist kein Pfad, sondern nur ein Name! Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Liest und setzt den Verzeichnisnamen, um Dokumentressourcen wie Bilder zu speichern. Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Liest und setzt die Erlaubnis, Tief- und Hochstellungen zu konvertieren. Dieser Wert ist standardmäßig true. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Liest und setzt die Erlaubnis, ein img-Tag zu verwenden, um Bilder links und rechts vom Text einzufügen. In diesem Fall wird im Markdown-Viewer der Text um das Bild herumfließen. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Erstellt eine Instanzoption zum Speichern eines Dokuments im Markdown-Format.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Lese oder setze einen rechteckigen Bereich, um Inhalt nach Markdown zu extrahieren.

**Returns:**
Rechteck-Instanz

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Liest oder setzt den Hervorhebungsstil für das erzeugte Dokument.

**Returns:**
EmphasisStyle-Element

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Liest und setzt eine Eigenschaft, die angibt, ob Vektorgrafiken extrahiert werden sollen.

**Returns:**
boolescher Wert

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Definiert die erwarteten Überschriftenebenen, die in der FontSize-Erkennungs-Header-Strategie verwendet werden. Wenn dieser Eigenschaftswert gesetzt ist, wird die Header-Erkennungsstrategie {@link HeadingRecognitionStrategy#Heuristic} ausgewählt, wenn {@link HeadingRecognitionStrategy#Auto} Strategien gesetzt sind, selbst wenn das Dokument Lesezeichen enthält.

**Returns:**
HeadingLevels Instanz

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Liest oder setzt die Header-Erkennungsstrategie.

**Returns:**
HeadingRecognitionStrategy Element

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Liest oder setzt den Überschriftsstil für das erzeugte Dokument.

**Returns:**
HeadingStyle Element

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Liest oder setzt den Zeilenumbruchstil für das erzeugte Dokument.

**Returns:**
LineBreakStyle Element

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Liest und setzt den Verzeichnisnamen, in dem Dokumentressourcen wie Bilder gespeichert werden. Wenn der Wert nicht angegeben ist, werden die Bilder in dasselbe Verzeichnis wie die Markdown-Datei selbst geschrieben. Dies ist kein Pfad, sondern nur ein Name! Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt.

**Returns:**
String Wert

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Liest und setzt den Verzeichnisnamen, um Dokumentressourcen wie Bilder zu speichern. Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt.

**Returns:**
String Wert

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Liest und setzt die Erlaubnis, Tief- und Hochstellungen zu konvertieren. Dieser Wert ist standardmäßig true.

**Returns:**
boolescher Wert

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Liest und setzt die Erlaubnis, ein img-Tag zu verwenden, um Bilder links und rechts vom Text einzufügen. In diesem Fall wird im Markdown-Viewer der Text um das Bild herumfließen.

**Returns:**
boolescher Wert

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Lese oder setze einen rechteckigen Bereich, um Inhalt nach Markdown zu extrahieren.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Liest oder setzt den Hervorhebungsstil für das erzeugte Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | EmphasisStyle-Element |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Liest und setzt eine Eigenschaft, die angibt, ob Vektorgrafiken extrahiert werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Definiert die erwarteten Überschriftenebenen, die in der FontSize-Erkennungs-Header-Strategie verwendet werden. Wenn dieser Eigenschaftswert gesetzt ist, wird die Header-Erkennungsstrategie {@link HeadingRecognitionStrategy#Heuristic} ausgewählt, wenn {@link HeadingRecognitionStrategy#Auto} Strategien gesetzt sind, selbst wenn das Dokument Lesezeichen enthält.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Liest oder setzt die Header-Erkennungsstrategie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | HeadingRecognitionStrategy Element |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Liest oder setzt den Überschriftsstil für das erzeugte Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | HeadingStyle Element |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Liest oder setzt den Zeilenumbruchstil für das erzeugte Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | LineBreakStyle Element |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Liest und setzt den Verzeichnisnamen, in dem Dokumentressourcen wie Bilder gespeichert werden. Wenn der Wert nicht angegeben ist, werden die Bilder in dasselbe Verzeichnis wie die Markdown-Datei selbst geschrieben. Dies ist kein Pfad, sondern nur ein Name! Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Liest und setzt den Verzeichnisnamen, um Dokumentressourcen wie Bilder zu speichern. Dieses Verzeichnis wird automatisch im Verzeichnis der gespeicherten Markdown-Datei erstellt.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Liest und setzt die Erlaubnis, Tief- und Hochstellungen zu konvertieren. Dieser Wert ist standardmäßig true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Liest und setzt die Erlaubnis, ein img-Tag zu verwenden, um Bilder links und rechts vom Text einzufügen. In diesem Fall wird im Markdown-Viewer der Text um das Bild herumfließen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
