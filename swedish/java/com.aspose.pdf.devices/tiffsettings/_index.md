---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass representerar inställningar för att importera pdf till Tiff."
type: docs
weight: 220
url: /sv/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Denna klass representerar inställningar för att importera pdf till Tiff.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Initierar en ny instans av klassen {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Initierar en ny instans av klassen {@code TiffSettings}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrightness](#getBrightness--) | Hämta värdegränsen för färgtransformeringen i vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Hämtar kompressionstypen. </p> Value: Kompressionstypen. <hr> <p> Standardvärdet är CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard. |
| [getDepth](#getDepth--) | <p> Hämtar färgdjupet. </p> Värde: Färgdjupet. <hr> <p> Standardvärdet är ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Hämtar IndexedConversionType. Standardvärdet är Simple. |
| [getMargins](#getMargins--) | Hämtar marginalerna. |
| [getShape](#getShape--) | <p> Hämtar typ av formen. </p> Värde: Typ av formen. <hr> <p> Standardvärdet är ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Hämtar ett värde som indikerar om tomma sidor ska hoppas över. </p> Värde: {@code true} om tomma sidor ska hoppas över; annars {@code false}. <hr> <p> Standardvärdet är false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Hämtar en flagga som bestämmer om alternativ bildbehandlingsmotor används eller inte. Sant värde används som standard för Linux OS. För Windows OS är standardvärdet false. |
| [setBrightness](#setBrightness-float-) | Ställ in värdegränsen för färgtransformeringen i vitt och svart. Denna parameter kan användas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Ställer in komprimeringstypen. </p> Värde: Komprimeringstypen. <hr> <p> Standardvärdet är CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Hämtar färgdjupet. </p> Värde: Färgdjupet. <hr> <p> Standardvärdet är ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Ställer in IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Ställer in typ av formen. </p> Värde: Typ av formen. <hr> <p> Standardvärdet är ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Ställer in ett värde som indikerar om tomma sidor ska hoppas över. </p> Värde: {@code true} om tomma sidor ska hoppas över; annars {@code false}. <hr> <p> Standardvärdet är false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Ställer in en flagga som bestämmer om alternativ bildbehandlingsmotor används eller inte. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Initierar en ny instans av klassen {@code TiffSettings}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skipBlankPages |  | om satt till {@code true} [hoppa över tomma sidor]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Initierar en ny instans av klassen {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Initierar en ny instans av klassen {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Hämta värdegränsen för färgtransformeringen i vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1

**Returns:**
flyttalsvärdet för ljusstyrka bör ligga i intervallet 0 till 1. Som standard är värdet lika med 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Hämtar kompressionstypen. </p> Value: Kompressionstypen. <hr> <p> Standardvärdet är CompressionType.LZW </p>

**Returns:**
CompressionType-element @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard.

**Returns:**
PageCoordinateType-värde @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Hämtar färgdjupet. </p> Värde: Färgdjupet. <hr> <p> Standardvärdet är ColorDepth.Default </p>

**Returns:**
ColorDepth-element @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Hämtar IndexedConversionType. Standardvärdet är Simple.

**Returns:**
IndexedConversionType-element @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Hämtar marginalerna.

**Returns:**
Marginalobjekt

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Hämtar typ av formen. </p> Värde: Typ av formen. <hr> <p> Standardvärdet är ShapeType.None </p>

**Returns:**
ShapeType-element @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Hämtar ett värde som indikerar om tomma sidor ska hoppas över. </p> Värde: {@code true} om tomma sidor ska hoppas över; annars {@code false}. <hr> <p> Standardvärdet är false </p>

**Returns:**
booleskt värde

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Hämtar en flagga som bestämmer om alternativ bildbehandlingsmotor används eller inte. Sant värde används som standard för Linux OS. För Windows OS är standardvärdet false.

**Returns:**
booleskt värde

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Ställ in värdegränsen för färgtransformeringen i vitt och svart. Denna parameter kan användas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | : Värdet för ljusstyrka bör ligga i intervallet 0 till 1. Som standard är värdet lika med 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Ställer in komprimeringstypen. </p> Värde: Komprimeringstypen. <hr> <p> Standardvärdet är CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Hämtar färgdjupet. </p> Värde: Färgdjupet. <hr> <p> Standardvärdet är ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Ställer in IndexedConversionType.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | IndexedConversionType-element @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Ställer in typ av formen. </p> Värde: Typ av formen. <hr> <p> Standardvärdet är ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Ställer in ett värde som indikerar om tomma sidor ska hoppas över. </p> Värde: {@code true} om tomma sidor ska hoppas över; annars {@code false}. <hr> <p> Standardvärdet är false </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Ställer in en flagga som bestämmer om alternativ bildbehandlingsmotor används eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useAlternativeImageEngine |  | booleskt värde |
