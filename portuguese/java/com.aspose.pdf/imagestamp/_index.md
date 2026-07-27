---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um selo gráfico."
type: docs
weight: 2360
url: /pt/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Representa um selo gráfico.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Inicializa uma nova instância da classe {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Cria um carimbo de imagem a partir de uma imagem no arquivo especificado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Fecha esta instância |
| [getAlternativeText](#getAlternativeText--) | Obtém o Texto Alternativo para o carimbo de imagem. |
| [getHeight](#getHeight--) | Obtém a altura da imagem. Definir esta imagem permite escalar a imagem verticalmente. |
| [getImage](#getImage--) | Obtém o fluxo de imagem usado para carimbar. |
| [getQuality](#getQuality--) | Obtém a qualidade do carimbo de imagem em porcentagem. Valores válidos são 0..100%. |
| [getWidth](#getWidth--) | Obtém a largura da imagem. Definir esta propriedade permite escalar a imagem horizontalmente. |
| [getXIndent](#getXIndent--) | Obtém e define a coordenada horizontal do carimbo, começando da esquerda. |
| [getYIndent](#getYIndent--) | Obtém e define a coordenada vertical do carimbo, começando da parte inferior. |
| [put](#put-com.aspose.pdf.Page-) | Adiciona um carimbo gráfico na página. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Define o Texto Alternativo para o carimbo de imagem. |
| [setHeight](#setHeight-double-) | Define a altura da imagem. Definir esta imagem permite escalar a imagem verticalmente. |
| [setQuality](#setQuality-int-) | Define a qualidade do carimbo de imagem em porcentagem. Valores válidos são 0..100%. |
| [setWidth](#setWidth-double-) | Define a largura da imagem. Definir esta propriedade permite escalar a imagem horizontalmente. |
| [setXIndent](#setXIndent-double-) | Obtém e define a coordenada horizontal do carimbo, começando da esquerda. |
| [setYIndent](#setYIndent-double-) | Obtém e define a coordenada vertical do carimbo, começando da parte inferior. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Inicializa uma nova instância da classe {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
Cria um carimbo de imagem a partir de uma imagem no arquivo especificado.

### close {#close--}
```
public void close()
```

Fecha esta instância

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtém o Texto Alternativo para o carimbo de imagem.

**Returns:**
valor String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém a altura da imagem. Definir esta imagem permite escalar a imagem verticalmente.

**Returns:**
valor double

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtém o fluxo de imagem usado para carimbar.

**Returns:**
objeto InputStream

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtém a qualidade do carimbo de imagem em porcentagem. Valores válidos são 0..100%.

**Returns:**
valor int

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura da imagem. Definir esta propriedade permite escalar a imagem horizontalmente.

**Returns:**
valor double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtém e define a coordenada horizontal do carimbo, começando da esquerda.

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtém e define a coordenada vertical do carimbo, começando da parte inferior.

**Returns:**
valor double

### put {#put-com.aspose.pdf.Page-}
Adiciona um carimbo gráfico na página.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Define o Texto Alternativo para o carimbo de imagem.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Define a altura da imagem. Definir esta imagem permite escalar a imagem verticalmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Define a qualidade do carimbo de imagem em porcentagem. Valores válidos são 0..100%.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura da imagem. Definir esta propriedade permite escalar a imagem horizontalmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Obtém e define a coordenada horizontal do carimbo, começando da esquerda.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Obtém e define a coordenada vertical do carimbo, começando da parte inferior.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
