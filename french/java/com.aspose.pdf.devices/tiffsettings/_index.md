---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente les paramètres d'importation de PDF vers TIFF."
type: docs
weight: 220
url: /fr/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Cette classe représente les paramètres d'importation de PDF vers TIFF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Initialise une nouvelle instance de la classe {@code TiffSettings}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrightness](#getBrightness--) | Obtient la limite de valeur de la transformation des couleurs en blanc et noir. Ce paramètre peut être appliqué avec EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Obtient le type de la compression. </p> Value: Le type de la compression. <hr> <p> La valeur par défaut est CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [getDepth](#getDepth--) | <p> Obtient la profondeur de couleur. </p> Value: La profondeur de couleur. <hr> <p> La valeur par défaut est ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Obtient le IndexedConversionType. La valeur par défaut est Simple. |
| [getMargins](#getMargins--) | Obtient les marges. |
| [getShape](#getShape--) | <p> Obtient le type de la forme. </p> Value: Le type de la forme. <hr> <p> La valeur par défaut est ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Obtient une valeur indiquant s'il faut ignorer les pages blanches. </p> Value: {@code true} si besoin d'ignorer les pages blanches ; sinon, {@code false}. <hr> <p> La valeur par défaut est false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Obtient un indicateur déterminant si le moteur d'imagerie alternatif est utilisé ou non. La valeur true est utilisée par défaut pour Linux OS. Pour Windows OS la valeur par défaut est false. |
| [setBrightness](#setBrightness-float-) | Définit la limite de valeur de la transformation des couleurs en blanc et noir. Ce paramètre peut être appliqué avec EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Définit le type de la compression. </p> Value: Le type de la compression. <hr> <p> La valeur par défaut est CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Obtient la profondeur de couleur. </p> Value: La profondeur de couleur. <hr> <p> La valeur par défaut est ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Définit le IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Définit le type de la forme. </p> Valeur: Le type de la forme. <hr> <p> La valeur par défaut est ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Définit une valeur indiquant s’il faut ignorer les pages blanches. </p> Valeur: {@code true} si besoin d’ignorer les pages blanches ; sinon, {@code false}. <hr> <p> La valeur par défaut est false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Définit un indicateur qui détermine si le moteur d’imagerie alternatif est utilisé ou non. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Initialise une nouvelle instance de la classe {@code TiffSettings}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| skipBlankPages |  | si défini sur {@code true} [ignorer les pages blanches]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Initialise une nouvelle instance de la classe {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Obtient la limite de valeur de la transformation des couleurs en blanc et noir. Ce paramètre peut être appliqué avec EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1

**Returns:**
la valeur flottante de la luminosité doit être comprise entre 0 et 1. Par défaut, la valeur est égale à 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Obtient le type de la compression. </p> Value: Le type de la compression. <hr> <p> La valeur par défaut est CompressionType.LZW </p>

**Returns:**
Élément CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

**Returns:**
Valeur PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Obtient la profondeur de couleur. </p> Value: La profondeur de couleur. <hr> <p> La valeur par défaut est ColorDepth.Default </p>

**Returns:**
Élément ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Obtient le IndexedConversionType. La valeur par défaut est Simple.

**Returns:**
Élément IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Obtient les marges.

**Returns:**
Objet Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Obtient le type de la forme. </p> Value: Le type de la forme. <hr> <p> La valeur par défaut est ShapeType.None </p>

**Returns:**
Élément ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Obtient une valeur indiquant s'il faut ignorer les pages blanches. </p> Value: {@code true} si besoin d'ignorer les pages blanches ; sinon, {@code false}. <hr> <p> La valeur par défaut est false </p>

**Returns:**
valeur booléenne

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Obtient un indicateur déterminant si le moteur d'imagerie alternatif est utilisé ou non. La valeur true est utilisée par défaut pour Linux OS. Pour Windows OS la valeur par défaut est false.

**Returns:**
valeur booléenne

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Définit la limite de valeur de la transformation des couleurs en blanc et noir. Ce paramètre peut être appliqué avec EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | : La valeur de la luminosité doit être comprise entre 0 et 1. Par défaut, la valeur est égale à 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Définit le type de la compression. </p> Value: Le type de la compression. <hr> <p> La valeur par défaut est CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Obtient la profondeur de couleur. </p> Value: La profondeur de couleur. <hr> <p> La valeur par défaut est ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Définit le IndexedConversionType.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Définit le type de la forme. </p> Valeur: Le type de la forme. <hr> <p> La valeur par défaut est ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Définit une valeur indiquant s’il faut ignorer les pages blanches. </p> Valeur: {@code true} si besoin d’ignorer les pages blanches ; sinon, {@code false}. <hr> <p> La valeur par défaut est false </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Définit un indicateur qui détermine si le moteur d’imagerie alternatif est utilisé ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useAlternativeImageEngine |  | valeur booléenne |
