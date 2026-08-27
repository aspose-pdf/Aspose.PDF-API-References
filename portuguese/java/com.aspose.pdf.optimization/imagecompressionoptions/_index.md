---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "A classe contém opções definidas para compressão de imagem."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

A classe contém opções definidas para compressão de imagem.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getEncoding](#getEncoding--) | Obtém ou define a codificação usada para armazenar imagens. |
| [getImageQuality](#getImageQuality--) | Especifica o nível de compressão de imagem quando a flag CompressImages é usada. |
| [getMaxResolution](#getMaxResolution--) | Especifica a resolução máxima das imagens. Se a imagem tiver resolução superior, ela será dimensionada. |
| [getResizeImages](#getResizeImages--) | Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| [getVersion](#getVersion--) | Versão do algoritmo de compressão. Valores possíveis são: 1. compressão padrão, 2. fast (compressão aprimorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mixed (compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode proporcionar a melhor compressão, porém mais lenta que o algoritmo \"fast\". A versão \"Fast\" não é aplicável ao redimensionamento de imagens (método padrão será usado). O padrão é \"Standard\". |
| [isCompressImages](#isCompressImages--) | Se esta flag for definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Se esta flag for definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| [setEncoding](#setEncoding-int-) | Obtém ou define a codificação usada para armazenar imagens. |
| [setImageQuality](#setImageQuality-int-) | Especifica o nível de compressão de imagem quando a flag CompressImages é usada. |
| [setMaxResolution](#setMaxResolution-int-) | Especifica a resolução máxima das imagens. Se a imagem tiver resolução superior, ela será dimensionada. |
| [setResizeImages](#setResizeImages-boolean-) | Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| [setVersion](#setVersion-int-) | Versão do algoritmo de compressão. Valores possíveis são: 1. compressão padrão, 2. fast (compressão aprimorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mixed (compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode proporcionar a melhor compressão, porém mais lenta que o algoritmo \"fast\". A versão \"Fast\" não é aplicável ao redimensionamento de imagens (método padrão será usado). O padrão é \"Standard\". |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Obtém ou define a codificação usada para armazenar imagens.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Especifica o nível de compressão de imagem quando a flag CompressImages é usada.

**Returns:**
valor int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Especifica a resolução máxima das imagens. Se a imagem tiver resolução superior, ela será dimensionada.

**Returns:**
valor int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado.

**Returns:**
valor booleano

### getVersion {#getVersion--}
```
public final int getVersion()
```

Versão do algoritmo de compressão. Valores possíveis são: 1. compressão padrão, 2. fast (compressão aprimorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mixed (compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode proporcionar a melhor compressão, porém mais lenta que o algoritmo \"fast\". A versão \"Fast\" não é aplicável ao redimensionamento de imagens (método padrão será usado). O padrão é \"Standard\".

**Returns:**
valor int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Se esta flag for definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality.

**Returns:**
valor booleano

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Se esta flag for definida como true, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Obtém ou define a codificação usada para armazenar imagens.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Especifica o nível de compressão de imagem quando a flag CompressImages é usada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Especifica a resolução máxima das imagens. Se a imagem tiver resolução superior, ela será dimensionada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Se esta flag estiver definida como true e CompressImages for true, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Versão do algoritmo de compressão. Valores possíveis são: 1. compressão padrão, 2. fast (compressão aprimorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mixed (compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode proporcionar a melhor compressão, porém mais lenta que o algoritmo \"fast\". A versão \"Fast\" não é aplicável ao redimensionamento de imagens (método padrão será usado). O padrão é \"Standard\".

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
