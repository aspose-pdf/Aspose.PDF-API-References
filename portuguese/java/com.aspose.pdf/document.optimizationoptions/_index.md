---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que descreve o algoritmo de otimização de documento. Instância desta classe pode ser usada como parâmetro do método OptimizeResources(). @deprecated Esta classe está obsoleta. Por favor."
type: docs
weight: 1110
url: /pt/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Classe que descreve o algoritmo de otimização de documento. Uma instância desta classe pode ser usada como parâmetro do método OptimizeResources(). @deprecated Esta classe está obsoleta. Por favor, use com.aspose.pdf.optimization.OptimizationOptions em vez disso.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Obsoleto. |

## Métodos

| Método | Descrição |
| --- | --- |
| [all](#all--) | Cria estratégia de otimização com todas as opções ativadas. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Especifica a dimensão máxima da imagem. Se a largura ou altura da imagem existente for maior que este valor, o tamanho da imagem será reduzido proporcionalmente. |
| [getResolution](#getResolution--) | Especifica o novo DPI da imagem quando a flag CompressIamges é usada. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Especifica a dimensão máxima da imagem. Se a largura ou altura da imagem existente for maior que este valor, o tamanho da imagem será reduzido proporcionalmente. |
| [setResolution](#setResolution-int-) | Especifica o novo DPI da imagem quando a flag CompressIamges é usada. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Obsoleto.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Cria estratégia de otimização com todas as opções ativadas.

**Returns:**
Objeto OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Especifica a dimensão máxima da imagem. Se a largura ou altura da imagem existente for maior que este valor, o tamanho da imagem será reduzido proporcionalmente.

**Returns:**
dimensão máxima da imagem

### getResolution {#getResolution--}
```
public int getResolution()
```

Especifica o novo DPI da imagem quando a flag CompressIamges é usada.

**Returns:**
resolução da imagem

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Especifica a dimensão máxima da imagem. Se a largura ou altura da imagem existente for maior que este valor, o tamanho da imagem será reduzido proporcionalmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dimensão |  | dimensão máxima da imagem |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Especifica o novo DPI da imagem quando a flag CompressIamges é usada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dpi |  | resolução da imagem |
