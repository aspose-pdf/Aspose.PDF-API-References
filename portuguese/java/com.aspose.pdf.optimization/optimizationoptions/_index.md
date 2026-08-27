---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que descreve o algoritmo de otimização de documento. Uma instância desta classe pode ser usada como parâmetro do método OptimizeResources()."
type: docs
weight: 40
url: /pt/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Classe que descreve o algoritmo de otimização de documento. Uma instância desta classe pode ser usada como parâmetro do método OptimizeResources().

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [all](#all--) | Cria uma estratégia de otimização com todas as opções ativadas. Observe que são ativadas apenas as opções que não alteram nenhuma funcionalidade do documento. Por exemplo, compressão de imagens e desincorporação de fontes não serão habilitadas (e podem ser incorporadas manualmente). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Se definido como {@link}, todos os fluxos de conteúdo de página não comprimidos serão comprimidos usando o filtro FlateDecode durante {@code Document#OptimizeResources()}. O padrão é {@link} para preservar a compatibilidade retroativa. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Conjunto de opções que descrevem como as imagens no documento serão comprimidas e os parâmetros da compressão. |
| [getImageEncoding](#getImageEncoding--) | Codificação de imagem que será usada. |
| [getImageQuality](#getImageQuality--) | Especifica o nível de compressão de imagem quando a flag CompressIamges é usada. |
| [getMaxResoultion](#getMaxResoultion--) | Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Se verdadeiro, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais. |
| [isCompressImages](#isCompressImages--) | Se este sinalizador estiver definido como verdadeiro, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Se este sinalizador estiver definido como {@code }, os objetos Pdf serão empacotados em Objest Streams e comprimidos para reduzir o tamanho do arquivo pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Se este sinalizador estiver definido como verdadeiro, os fluxos de Recursos serão analisados. Se fluxos duplicados forem encontrados (ou seja, se o conteúdo do fluxo for igual), então esses fluxos serão armazenados como um único objeto. Isso permite diminuir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Remover informações privadas (informações de fragmento de página). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Se este sinalizador estiver definido como verdadeiro, todos os objetos do documento serão verificados e os objetos não utilizados (ou seja, objetos que não têm nenhuma referência) são removidos do documento. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Se este sinalizador estiver definido como verdadeiro, cada recurso será verificado quanto ao seu uso. Se o recurso nunca for usado, ele será removido. Isso pode diminuir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento. |
| [isResizeImages](#isResizeImages--) | Se este sinalizador estiver definido como verdadeiro e CompressImages for verdadeiro, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| [isSubsetFonts](#isSubsetFonts--) | As fontes serão convertidas em subconjuntos se definidas como verdadeiro. |
| [isUnembedFonts](#isUnembedFonts--) | Não incorporar fontes se definido como verdadeiro. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Se verdadeiro, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Se definido como {@link}, todos os fluxos de conteúdo de página não comprimidos serão comprimidos usando o filtro FlateDecode durante {@code Document#OptimizeResources()}. O padrão é {@link} para preservar a compatibilidade retroativa. |
| [setCompressImages](#setCompressImages-boolean-) | Se este sinalizador estiver definido como verdadeiro, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Se este sinalizador estiver definido como {@code }, os objetos Pdf serão empacotados em Objest Streams e comprimidos para reduzir o tamanho do arquivo pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Conjunto de opções que descrevem como as imagens no documento serão comprimidas e os parâmetros da compressão. |
| [setImageEncoding](#setImageEncoding-int-) | Codificação de imagem que será usada. |
| [setImageQuality](#setImageQuality-int-) | Especifica o nível de compressão de imagem quando a flag CompressIamges é usada. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Se este sinalizador estiver definido como verdadeiro, os fluxos de Recursos serão analisados. Se fluxos duplicados forem encontrados (ou seja, se o conteúdo do fluxo for igual), então esses fluxos serão armazenados como um único objeto. Isso permite diminuir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes). |
| [setMaxResoultion](#setMaxResoultion-int-) | Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Remover informações privadas (informações de fragmento de página). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Se este sinalizador estiver definido como verdadeiro, todos os objetos do documento serão verificados e os objetos não utilizados (ou seja, objetos que não têm nenhuma referência) são removidos do documento. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Se este sinalizador estiver definido como verdadeiro, cada recurso será verificado quanto ao seu uso. Se o recurso nunca for usado, ele será removido. Isso pode diminuir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento. |
| [setResizeImages](#setResizeImages-boolean-) | Se este sinalizador estiver definido como verdadeiro e CompressImages for verdadeiro, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | As fontes serão convertidas em subconjuntos se definidas como verdadeiro. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Não incorporar fontes se definido como verdadeiro. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Cria uma estratégia de otimização com todas as opções ativadas. Observe que são ativadas apenas as opções que não alteram nenhuma funcionalidade do documento. Por exemplo, compressão de imagens e desincorporação de fontes não serão habilitadas (e podem ser incorporadas manualmente).

**Returns:**
Objeto OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Se definido como {@link}, todos os fluxos de conteúdo de página não comprimidos serão comprimidos usando o filtro FlateDecode durante {@code Document#OptimizeResources()}. O padrão é {@link} para preservar a compatibilidade retroativa.

**Returns:**
valor booleano

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Conjunto de opções que descrevem como as imagens no documento serão comprimidas e os parâmetros da compressão.

**Returns:**
Instância ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Codificação de imagem que será usada.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Especifica o nível de compressão de imagem quando a flag CompressIamges é usada.

**Returns:**
valor int @deprecated Por favor, use ImageCompressionOptions.ImageQuality em vez disso.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada.

**Returns:**
valor int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Se verdadeiro, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais.

**Returns:**
valor booleano

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Se este sinalizador estiver definido como verdadeiro, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality.

**Returns:**
valor boolean @deprecated Por favor, use ImageCompressionOptions.CompressImages em vez disso.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Se este sinalizador estiver definido como {@code }, os objetos Pdf serão empacotados em Objest Streams e comprimidos para reduzir o tamanho do arquivo pdf.

**Returns:**
valor booleano

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Se este sinalizador estiver definido como verdadeiro, os fluxos de Recursos serão analisados. Se fluxos duplicados forem encontrados (ou seja, se o conteúdo do fluxo for igual), então esses fluxos serão armazenados como um único objeto. Isso permite diminuir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes).

**Returns:**
valor booleano

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Remover informações privadas (informações de fragmento de página).

**Returns:**
valor booleano

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Se este sinalizador estiver definido como verdadeiro, todos os objetos do documento serão verificados e os objetos não utilizados (ou seja, objetos que não têm nenhuma referência) são removidos do documento.

**Returns:**
valor booleano

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Se este sinalizador estiver definido como verdadeiro, cada recurso será verificado quanto ao seu uso. Se o recurso nunca for usado, ele será removido. Isso pode diminuir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento.

**Returns:**
valor booleano

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Se este sinalizador estiver definido como verdadeiro e CompressImages for verdadeiro, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado.

**Returns:**
valor boolean @deprecated Por favor, use ImageCompressionOptions.ResizeImages em vez disso.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

As fontes serão convertidas em subconjuntos se definidas como verdadeiro.

**Returns:**
valor booleano

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Não incorporar fontes se definido como verdadeiro.

**Returns:**
valor booleano

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Se verdadeiro, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Se definido como {@link}, todos os fluxos de conteúdo de página não comprimidos serão comprimidos usando o filtro FlateDecode durante {@code Document#OptimizeResources()}. O padrão é {@link} para preservar a compatibilidade retroativa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Se este sinalizador estiver definido como verdadeiro, as imagens serão comprimidas no documento. O nível de compressão é especificado com a propriedade ImageQuality.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor boolean @deprecated Por favor, use ImageCompressionOptions.CompressImages em vez disso. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Se este sinalizador estiver definido como {@code }, os objetos Pdf serão empacotados em Objest Streams e comprimidos para reduzir o tamanho do arquivo pdf.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Conjunto de opções que descrevem como as imagens no documento serão comprimidas e os parâmetros da compressão.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Codificação de imagem que será usada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Especifica o nível de compressão de imagem quando a flag CompressIamges é usada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @deprecated Por favor, use ImageCompressionOptions.ImageQuality em vez disso. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Se este sinalizador estiver definido como verdadeiro, os fluxos de Recursos serão analisados. Se fluxos duplicados forem encontrados (ou seja, se o conteúdo do fluxo for igual), então esses fluxos serão armazenados como um único objeto. Isso permite diminuir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Especifica a resolução máxima das imagens. Se a imagem tiver resolução maior, ela será redimensionada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Remover informações privadas (informações de fragmento de página).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Se este sinalizador estiver definido como verdadeiro, todos os objetos do documento serão verificados e os objetos não utilizados (ou seja, objetos que não têm nenhuma referência) são removidos do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Se este sinalizador estiver definido como verdadeiro, cada recurso será verificado quanto ao seu uso. Se o recurso nunca for usado, ele será removido. Isso pode diminuir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Se este sinalizador estiver definido como verdadeiro e CompressImages for verdadeiro, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor boolean @deprecated Por favor, use ImageCompressionOptions.ResizeImages em vez disso. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

As fontes serão convertidas em subconjuntos se definidas como verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Não incorporar fontes se definido como verdadeiro.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
