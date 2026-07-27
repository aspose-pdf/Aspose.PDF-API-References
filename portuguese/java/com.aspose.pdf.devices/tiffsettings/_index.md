---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa as configurações para importar pdf para Tiff."
type: docs
weight: 220
url: /pt/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Esta classe representa as configurações para importar pdf para Tiff.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Inicializa uma nova instância da classe {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Inicializa uma nova instância da classe {@code TiffSettings}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBrightness](#getBrightness--) | Obtém o limite de valor da transformação de cores em branco e preto. Este parâmetro pode ser aplicado com EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Obtém o tipo da compressão. </p> Value: O tipo da compressão. <hr> <p> O valor padrão é CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [getDepth](#getDepth--) | <p> Obtém a profundidade de cor. </p> Value: A profundidade de cor. <hr> <p> O valor padrão é ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Obtém o IndexedConversionType. O valor padrão é Simple. |
| [getMargins](#getMargins--) | Obtém as margens. |
| [getShape](#getShape--) | <p> Obtém o tipo da forma. </p> Value: O tipo da forma. <hr> <p> O valor padrão é ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Obtém um valor que indica se deve pular páginas em branco. </p> Value: {@code true} se for necessário pular páginas em branco; caso contrário, {@code false}. <hr> <p> O valor padrão é false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Obtém um sinalizador que determina se o motor de imagens alternativo é usado ou não. O valor true é usado por padrão para Linux OS. Para Windows OS o valor padrão é false. |
| [setBrightness](#setBrightness-float-) | Define o limite de valor da transformação de cores em branco e preto. Este parâmetro pode ser aplicado com EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Define o tipo da compressão. </p> Value: O tipo da compressão. <hr> <p> O valor padrão é CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Obtém a profundidade de cor. </p> Value: A profundidade de cor. <hr> <p> O valor padrão é ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Define o IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Define o tipo da forma. </p> Valor: O tipo da forma. <hr> <p> O valor padrão é ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Define um valor que indica se deve pular páginas em branco. </p> Valor: {@code true} se for necessário pular páginas em branco; caso contrário, {@code false}. <hr> <p> O valor padrão é false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Define um indicador que determina se o motor de imagens alternativo é usado ou não. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Inicializa uma nova instância da classe {@code TiffSettings}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| skipBlankPages |  | se definido como {@code true} [pular páginas em branco]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Inicializa uma nova instância da classe {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Obtém o limite de valor da transformação de cores em branco e preto. Este parâmetro pode ser aplicado com EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1

**Returns:**
o valor float de brilho deve estar no intervalo de 0 a 1. Por padrão, o valor é igual a 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Obtém o tipo da compressão. </p> Value: O tipo da compressão. <hr> <p> O valor padrão é CompressionType.LZW </p>

**Returns:**
elemento CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtém o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

**Returns:**
valor PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Obtém a profundidade de cor. </p> Value: A profundidade de cor. <hr> <p> O valor padrão é ColorDepth.Default </p>

**Returns:**
elemento ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Obtém o IndexedConversionType. O valor padrão é Simple.

**Returns:**
elemento IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Obtém as margens.

**Returns:**
objeto Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Obtém o tipo da forma. </p> Value: O tipo da forma. <hr> <p> O valor padrão é ShapeType.None </p>

**Returns:**
elemento ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Obtém um valor que indica se deve pular páginas em branco. </p> Value: {@code true} se for necessário pular páginas em branco; caso contrário, {@code false}. <hr> <p> O valor padrão é false </p>

**Returns:**
valor booleano

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Obtém um sinalizador que determina se o motor de imagens alternativo é usado ou não. O valor true é usado por padrão para Linux OS. Para Windows OS o valor padrão é false.

**Returns:**
valor booleano

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Define o limite de valor da transformação de cores em branco e preto. Este parâmetro pode ser aplicado com EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | : O valor de brilho deve estar no intervalo de 0 a 1. Por padrão, o valor é igual a 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Define o tipo da compressão. </p> Value: O tipo da compressão. <hr> <p> O valor padrão é CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Obtém a profundidade de cor. </p> Value: A profundidade de cor. <hr> <p> O valor padrão é ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Define o IndexedConversionType.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | elemento IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Define o tipo da forma. </p> Valor: O tipo da forma. <hr> <p> O valor padrão é ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Define um valor que indica se deve pular páginas em branco. </p> Valor: {@code true} se for necessário pular páginas em branco; caso contrário, {@code false}. <hr> <p> O valor padrão é false </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Define um indicador que determina se o motor de imagens alternativo é usado ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| useAlternativeImageEngine |  | valor booleano |
