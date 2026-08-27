---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe rappresenta le impostazioni per l'importazione di pdf in Tiff."
type: docs
weight: 220
url: /it/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Questa classe rappresenta le impostazioni per l'importazione di pdf in Tiff.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Inizializza una nuova istanza della classe {@code TiffSettings}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrightness](#getBrightness--) | Ottieni il limite di valore della trasformazione dei colori in bianco e nero. Questo parametro può essere applicato con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Ottiene il tipo di compressione. </p> Value: Il tipo di compressione. <hr> <p> Il valore predefinito è CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [getDepth](#getDepth--) | <p> Ottiene la profondità di colore. </p> Value: La profondità di colore. <hr> <p> Il valore predefinito è ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Ottiene l'IndexedConversionType. Il valore predefinito è Simple. |
| [getMargins](#getMargins--) | Ottiene i margini. |
| [getShape](#getShape--) | <p> Ottiene il tipo di forma. </p> Value: Il tipo di forma. <hr> <p> Il valore predefinito è ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Ottiene un valore che indica se saltare le pagine vuote. </p> Value: {@code true} se è necessario saltare le pagine vuote; altrimenti, {@code false}. <hr> <p> Il valore predefinito è false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Ottiene un flag che determina se viene utilizzato o meno il motore di imaging alternativo. Il valore true è usato per impostazione predefinita su Linux OS. Per Windows OS il valore predefinito è false. |
| [setBrightness](#setBrightness-float-) | Imposta il limite di valore della trasformazione dei colori in bianco e nero. Questo parametro può essere applicato con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Imposta il tipo di compressione. </p> Value: Il tipo di compressione. <hr> <p> Il valore predefinito è CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Ottiene la profondità di colore. </p> Value: La profondità di colore. <hr> <p> Il valore predefinito è ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Imposta l'IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Imposta il tipo della forma. </p> Value: Il tipo della forma. <hr> <p> Il valore predefinito è ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Imposta un valore che indica se saltare le pagine vuote. </p> Value: {@code true} se è necessario saltare le pagine vuote; altrimenti, {@code false}. <hr> <p> Il valore predefinito è false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Imposta un flag che determina se il motore di imaging alternativo è utilizzato o meno. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Inizializza una nuova istanza della classe {@code TiffSettings}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| skipBlankPages |  | se impostato su {@code true} [salta pagine vuote]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Inizializza una nuova istanza della classe {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Ottieni il limite di valore della trasformazione dei colori in bianco e nero. Questo parametro può essere applicato con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1

**Returns:**
Il valore float della luminosità deve essere nell'intervallo da 0 a 1. Per impostazione predefinita il valore è pari a 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Ottiene il tipo di compressione. </p> Value: Il tipo di compressione. <hr> <p> Il valore predefinito è CompressionType.LZW </p>

**Returns:**
Elemento CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ottiene il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

**Returns:**
Valore PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Ottiene la profondità di colore. </p> Value: La profondità di colore. <hr> <p> Il valore predefinito è ColorDepth.Default </p>

**Returns:**
Elemento ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Ottiene l'IndexedConversionType. Il valore predefinito è Simple.

**Returns:**
Elemento IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Ottiene i margini.

**Returns:**
Oggetto Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Ottiene il tipo di forma. </p> Value: Il tipo di forma. <hr> <p> Il valore predefinito è ShapeType.None </p>

**Returns:**
Elemento ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Ottiene un valore che indica se saltare le pagine vuote. </p> Value: {@code true} se è necessario saltare le pagine vuote; altrimenti, {@code false}. <hr> <p> Il valore predefinito è false </p>

**Returns:**
valore booleano

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Ottiene un flag che determina se viene utilizzato o meno il motore di imaging alternativo. Il valore true è usato per impostazione predefinita su Linux OS. Per Windows OS il valore predefinito è false.

**Returns:**
valore booleano

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Imposta il limite di valore della trasformazione dei colori in bianco e nero. Questo parametro può essere applicato con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | : Il valore della luminosità deve essere nell'intervallo da 0 a 1. Per impostazione predefinita il valore è pari a 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Imposta il tipo di compressione. </p> Value: Il tipo di compressione. <hr> <p> Il valore predefinito è CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Imposta il tipo di coordinate della pagina (box Media/Crop). Il valore CropBox è usato per impostazione predefinita.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Ottiene la profondità di colore. </p> Value: La profondità di colore. <hr> <p> Il valore predefinito è ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Imposta l'IndexedConversionType.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Imposta il tipo della forma. </p> Value: Il tipo della forma. <hr> <p> Il valore predefinito è ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Imposta un valore che indica se saltare le pagine vuote. </p> Value: {@code true} se è necessario saltare le pagine vuote; altrimenti, {@code false}. <hr> <p> Il valore predefinito è false </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Imposta un flag che determina se il motore di imaging alternativo è utilizzato o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useAlternativeImageEngine |  | valore booleano |
