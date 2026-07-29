---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse repräsentiert Einstellungen für den Import von PDF nach TIFF."
type: docs
weight: 220
url: /de/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Diese Klasse repräsentiert Einstellungen für den Import von PDF nach TIFF.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-boolean-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBrightness](#getBrightness--) | Ermittelt den Grenzwert der Farbumwandlung in Weiß und Schwarz. Dieser Parameter kann mit EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle oder ColorDepth.Format1bpp == 1 verwendet werden. |
| [getCompression](#getCompression--) | <p> Gibt den Kompressionstyp zurück. </p> Value: Der Typ der Kompression. <hr> <p> Standardwert ist CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [getDepth](#getDepth--) | <p> Gibt die Farbtiefe zurück. </p> Value: Die Farbtiefe. <hr> <p> Standardwert ist ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Gibt den IndexedConversionType zurück. Standardwert ist Simple. |
| [getMargins](#getMargins--) | Gibt die Ränder zurück. |
| [getShape](#getShape--) | <p> Gibt den Formtyp zurück. </p> Value: Der Typ der Form. <hr> <p> Standardwert ist ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Gibt einen Wert zurück, der angibt, ob leere Seiten übersprungen werden sollen. </p> Value: {@code true}, wenn leere Seiten übersprungen werden sollen; andernfalls {@code false}. <hr> <p> Standardwert ist false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Gibt ein Flag zurück, das bestimmt, ob die alternative Bildverarbeitungs-Engine verwendet wird oder nicht. Der Wert true wird standardmäßig für Linux OS verwendet. Für Windows OS ist der Standardwert false. |
| [setBrightness](#setBrightness-float-) | Setzt den Grenzwert der Farbumwandlung in Weiß und Schwarz. Dieser Parameter kann mit EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle oder ColorDepth.Format1bpp == 1 verwendet werden. |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Legt den Kompressionstyp fest. </p> Value: Der Typ der Kompression. <hr> <p> Standardwert ist CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Gibt die Farbtiefe zurück. </p> Value: Die Farbtiefe. <hr> <p> Standardwert ist ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Legt den IndexedConversionType fest. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Legt den Formtyp fest. </p> Value: Der Typ der Form. <hr> <p> Standardwert ist ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Legt einen Wert fest, der angibt, ob leere Seiten übersprungen werden sollen. </p> Wert: {@code true} wenn leere Seiten übersprungen werden sollen; andernfalls {@code false}. <hr> <p> Standardwert ist false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Setzt ein Flag, das bestimmt, ob die alternative Bild-Engine verwendet wird oder nicht. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skipBlankPages |  | wenn auf {@code true} gesetzt [leere Seiten überspringen]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Initialisiert eine neue Instanz der {@code TiffSettings}-Klasse.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Ermittelt den Grenzwert der Farbumwandlung in Weiß und Schwarz. Dieser Parameter kann mit EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle oder ColorDepth.Format1bpp == 1 verwendet werden.

**Returns:**
Der Gleitkommawert der Helligkeit sollte im Bereich von 0 bis 1 liegen. Standardmäßig ist der Wert gleich 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Gibt den Kompressionstyp zurück. </p> Value: Der Typ der Kompression. <hr> <p> Standardwert ist CompressionType.LZW </p>

**Returns:**
CompressionType-Element @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

**Returns:**
PageCoordinateType-Wert @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Gibt die Farbtiefe zurück. </p> Value: Die Farbtiefe. <hr> <p> Standardwert ist ColorDepth.Default </p>

**Returns:**
ColorDepth-Element @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Gibt den IndexedConversionType zurück. Standardwert ist Simple.

**Returns:**
IndexedConversionType-Element @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Gibt die Ränder zurück.

**Returns:**
Margins-Objekt

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Gibt den Formtyp zurück. </p> Value: Der Typ der Form. <hr> <p> Standardwert ist ShapeType.None </p>

**Returns:**
ShapeType-Element @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Gibt einen Wert zurück, der angibt, ob leere Seiten übersprungen werden sollen. </p> Value: {@code true}, wenn leere Seiten übersprungen werden sollen; andernfalls {@code false}. <hr> <p> Standardwert ist false </p>

**Returns:**
boolescher Wert

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Gibt ein Flag zurück, das bestimmt, ob die alternative Bildverarbeitungs-Engine verwendet wird oder nicht. Der Wert true wird standardmäßig für Linux OS verwendet. Für Windows OS ist der Standardwert false.

**Returns:**
boolescher Wert

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Setzt den Grenzwert der Farbumwandlung in Weiß und Schwarz. Dieser Parameter kann mit EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle oder ColorDepth.Format1bpp == 1 verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | : Der Wert der Helligkeit sollte im Bereich von 0 bis 1 liegen. Standardmäßig ist der Wert gleich 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Legt den Kompressionstyp fest. </p> Value: Der Typ der Kompression. <hr> <p> Standardwert ist CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Gibt die Farbtiefe zurück. </p> Value: Die Farbtiefe. <hr> <p> Standardwert ist ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Legt den IndexedConversionType fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | IndexedConversionType-Element @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Legt den Formtyp fest. </p> Value: Der Typ der Form. <hr> <p> Standardwert ist ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Legt einen Wert fest, der angibt, ob leere Seiten übersprungen werden sollen. </p> Wert: {@code true} wenn leere Seiten übersprungen werden sollen; andernfalls {@code false}. <hr> <p> Standardwert ist false </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Setzt ein Flag, das bestimmt, ob die alternative Bild-Engine verwendet wird oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useAlternativeImageEngine |  | boolescher Wert |
