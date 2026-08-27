---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Rendering-Optionen dar"
type: docs
weight: 4150
url: /de/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Stellt Rendering-Optionen dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Initialisiert eine neue Instanz des {@code RenderingOptions}-Objekts. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Schriftart‑Ersetzungsalgorithmus folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName explizit festlegt, prüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen darstellen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, durchsuchen Sie die über {@code FontRepository.Sources} hinzugefügten Schriften. 3. Analysieren Sie den Text, um dessen Alphabet oder Skript zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriften im System zu finden und zu verwenden. 4. Als Rückfall durchsuchen Sie das System nach einer Schriftart, die die erforderlichen Zeichen darstellen kann. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Ruft den Barcode‑Optimierungsmodus ab. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Zeigt an, dass alle Schriftarten in TTF‑Unicode‑Versionen konvertiert werden. Das ist aus Kompatibilitätsgründen und zur Optimierung der Schriftartnutzung nützlich, da jede neue TTF‑Schrift nicht alle Symbole der Quellschrift enthält, sondern nur die im Text verwendeten Symbole. |
| [getDefaultFontName](#getDefaultFontName--) | Ruft/legt den Standardnamen der Schriftart fest, die zum Ersetzen fehlender Schriftarten verwendet wird. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Liest oder setzt den Hochqualitätsmodus für die Interpolation. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Maximale Anzahl von Schriftarten im Schriftarten‑Cache. Standardwert ist 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Maximale Anzahl von Symbolen im Symbol‑Cache. Standardwert ist 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Liest oder setzt den Modus zur Optimierung von Abmessungen. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Liest oder setzt einen Wert, der verwendet wird, um alle Bilder auf der Seite zu skalieren, damit sie in die Seitenbreite passen. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Liest einen Modus, in dem Systemschriftarten nativ gerendert werden |
| [getUseFontHinting](#getUseFontHinting--) | Die Verwendung dieses Flags aktiviert den Font‑Hinting‑Mechanismus. Font Hinting ist die Verwendung mathematischer Anweisungen, um die Darstellung einer Konturschrift anzupassen. In einigen Fällen kann das Einschalten dieses Flags Probleme mit der Lesbarkeit von Text lösen. Zum gegenwärtigen Zeitpunkt wirkt sich die Verwendung dieses Flags nur auf TTF‑Schriften aus, wenn diese Schriften im Quelldokument verwendet werden. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Liest ein Flag, das bestimmt, ob die neue Imaging‑Engine verwendet wird oder nicht. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Liest einen Wert, der verwendet wird, um Fehler beim Verarbeiten einer PDF‑Datei zu überspringen |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Schriftart‑Ersetzungsalgorithmus folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName explizit festlegt, prüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen darstellen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, durchsuchen Sie die über {@code FontRepository.Sources} hinzugefügten Schriften. 3. Analysieren Sie den Text, um dessen Alphabet oder Skript zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriften im System zu finden und zu verwenden. 4. Als Rückfall durchsuchen Sie das System nach einer Schriftart, die die erforderlichen Zeichen darstellen kann. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Setzt den Barcode‑Optimierungsmodus. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Zeigt an, dass alle Schriftarten in TTF‑Unicode‑Versionen konvertiert werden. Das ist aus Kompatibilitätsgründen und zur Optimierung der Schriftartnutzung nützlich, da jede neue TTF‑Schrift nicht alle Symbole der Quellschrift enthält, sondern nur die im Text verwendeten Symbole. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Ruft/legt den Standardnamen der Schriftart fest, die zum Ersetzen fehlender Schriftarten verwendet wird. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Liest oder setzt den Hochqualitätsmodus für die Interpolation. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Maximale Anzahl von Schriftarten im Schriftarten‑Cache. Standardwert ist 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Maximale Anzahl von Symbolen im Symbol‑Cache. Standardwert ist 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Liest oder setzt den Modus zur Optimierung von Abmessungen. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Liest oder setzt einen Wert, der verwendet wird, um alle Bilder auf der Seite zu skalieren, damit sie in die Seitenbreite passen. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Setzt einen Modus, in dem Systemschriftarten nativ gerendert werden |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Setzt einen Wert, der verwendet wird, um Fehler beim Verarbeiten einer PDF‑Datei zu überspringen |
| [setUseFontHinting](#setUseFontHinting-boolean-) | Die Verwendung dieses Flags aktiviert den Font‑Hinting‑Mechanismus. Font Hinting ist die Verwendung mathematischer Anweisungen, um die Darstellung einer Konturschrift anzupassen. In einigen Fällen kann das Einschalten dieses Flags Probleme mit der Lesbarkeit von Text lösen. Zum gegenwärtigen Zeitpunkt wirkt sich die Verwendung dieses Flags nur auf TTF‑Schriften aus, wenn diese Schriften im Quelldokument verwendet werden. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Setzt ein Flag, das bestimmt, ob die neue Imaging‑Engine verwendet wird oder nicht. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Initialisiert eine neue Instanz des {@code RenderingOptions}-Objekts.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Schriftart‑Ersetzungsalgorithmus folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName explizit festlegt, prüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen darstellen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, durchsuchen Sie die über {@code FontRepository.Sources} hinzugefügten Schriften. 3. Analysieren Sie den Text, um dessen Alphabet oder Skript zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriften im System zu finden und zu verwenden. 4. Als Rückfall durchsuchen Sie das System nach einer Schriftart, die die erforderlichen Zeichen darstellen kann.

**Returns:**
boolescher Wert

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Ruft den Barcode‑Optimierungsmodus ab.

**Returns:**
boolescher Wert

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Zeigt an, dass alle Schriftarten in TTF‑Unicode‑Versionen konvertiert werden. Das ist aus Kompatibilitätsgründen und zur Optimierung der Schriftartnutzung nützlich, da jede neue TTF‑Schrift nicht alle Symbole der Quellschrift enthält, sondern nur die im Text verwendeten Symbole.

**Returns:**
boolescher Wert

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Ruft/legt den Standardnamen der Schriftart fest, die zum Ersetzen fehlender Schriftarten verwendet wird.

**Returns:**
String Wert

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern.

**Returns:**
float-Wert

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig.

**Returns:**
boolescher Wert

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Liest oder setzt den Hochqualitätsmodus für die Interpolation.

**Returns:**
boolescher Wert

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Maximale Anzahl von Schriftarten im Schriftarten‑Cache. Standardwert ist 10.

**Returns:**
int-Wert

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Maximale Anzahl von Symbolen im Symbol‑Cache. Standardwert ist 100.

**Returns:**
int-Wert

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Liest oder setzt den Modus zur Optimierung von Abmessungen.

**Returns:**
boolescher Wert

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Liest oder setzt einen Wert, der verwendet wird, um alle Bilder auf der Seite zu skalieren, damit sie in die Seitenbreite passen.

**Returns:**
boolescher Wert @deprecated ScaleImagesToFitPageWidth ist veraltet.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Liest einen Modus, in dem Systemschriftarten nativ gerendert werden

**Returns:**
boolescher Wert

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

Die Verwendung dieses Flags aktiviert den Font‑Hinting‑Mechanismus. Font Hinting ist die Verwendung mathematischer Anweisungen, um die Darstellung einer Konturschrift anzupassen. In einigen Fällen kann das Einschalten dieses Flags Probleme mit der Lesbarkeit von Text lösen. Zum gegenwärtigen Zeitpunkt wirkt sich die Verwendung dieses Flags nur auf TTF‑Schriften aus, wenn diese Schriften im Quelldokument verwendet werden.

**Returns:**
boolescher Wert

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Liest ein Flag, das bestimmt, ob die neue Imaging‑Engine verwendet wird oder nicht.

**Returns:**
boolescher Wert @deprecated UseNewImagingEngine ist veraltet

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern.

**Returns:**
float-Wert

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Liest einen Wert, der verwendet wird, um Fehler beim Verarbeiten einer PDF‑Datei zu überspringen

**Returns:**
boolescher Wert

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Schriftart‑Ersetzungsalgorithmus folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName explizit festlegt, prüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen darstellen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, durchsuchen Sie die über {@code FontRepository.Sources} hinzugefügten Schriften. 3. Analysieren Sie den Text, um dessen Alphabet oder Skript zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriften im System zu finden und zu verwenden. 4. Als Rückfall durchsuchen Sie das System nach einer Schriftart, die die erforderlichen Zeichen darstellen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Setzt den Barcode‑Optimierungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Zeigt an, dass alle Schriftarten in TTF‑Unicode‑Versionen konvertiert werden. Das ist aus Kompatibilitätsgründen und zur Optimierung der Schriftartnutzung nützlich, da jede neue TTF‑Schrift nicht alle Symbole der Quellschrift enthält, sondern nur die im Text verwendeten Symbole.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Ruft/legt den Standardnamen der Schriftart fest, die zum Ersetzen fehlender Schriftarten verwendet wird.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Liest oder setzt den Hochqualitätsmodus für die Interpolation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Maximale Anzahl von Schriftarten im Schriftarten‑Cache. Standardwert ist 10.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Maximale Anzahl von Symbolen im Symbol‑Cache. Standardwert ist 100.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Liest oder setzt den Modus zur Optimierung von Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Liest oder setzt einen Wert, der verwendet wird, um alle Bilder auf der Seite zu skalieren, damit sie in die Seitenbreite passen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated ScaleImagesToFitPageWidth ist veraltet. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Setzt einen Modus, in dem Systemschriftarten nativ gerendert werden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Setzt einen Wert, der verwendet wird, um Fehler beim Verarbeiten einer PDF‑Datei zu überspringen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

Die Verwendung dieses Flags aktiviert den Font‑Hinting‑Mechanismus. Font Hinting ist die Verwendung mathematischer Anweisungen, um die Darstellung einer Konturschrift anzupassen. In einigen Fällen kann das Einschalten dieses Flags Probleme mit der Lesbarkeit von Text lösen. Zum gegenwärtigen Zeitpunkt wirkt sich die Verwendung dieses Flags nur auf TTF‑Schriften aus, wenn diese Schriften im Quelldokument verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Setzt ein Flag, das bestimmt, ob die neue Imaging‑Engine verwendet wird oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated UseNewImagingEngine ist veraltet |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Liest oder setzt einen Wert, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu vergrößern oder zu verkleinern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |
