---
title: "Título"
linktitle: "Título"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o cabeçalho."
type: docs
weight: 1890
url: /pt/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Representa o cabeçalho.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Heading](#Heading--) | Somente para uso interno |
| [Heading](#Heading-int-) | Inicializa uma nova instância da classe Cell. |

## Métodos

| Método | Descrição |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona o título com todos os segmentos. |
| [deepClone](#deepClone--) | Clona o título. |
| [getDestinationPage](#getDestinationPage--) | Obtém a página de destino. |
| [getLevel](#getLevel--) | Obtém o nível. |
| [getStartNumber](#getStartNumber--) | Obtém o número inicial do título. |
| [getStyle](#getStyle--) | Obtém ou define o estilo. |
| [getTocPage](#getTocPage--) | Obtém a página que contém este título. |
| [getTop](#getTop--) | Obtém o Y superior destes títulos (para uso interno). |
| [getUserLabel](#getUserLabel--) | Obtém ou define o rótulo do usuário. |
| [isAutoSequence](#isAutoSequence--) | Obtém se o título deve ser numerado automaticamente. |
| [isInList](#isInList--) | Obtém se o título deve estar na lista de índice. |
| [setAutoSequence](#setAutoSequence-boolean-) | Define se o título deve ser numerado automaticamente. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Define a página de destino. |
| [setInList](#setInList-boolean-) | Define se o título deve estar na lista de índice. |
| [setLevel](#setLevel-int-) | define o nível. |
| [setStartNumber](#setStartNumber-int-) | Obtém o número inicial do cabeçalho. Valor: O startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | define ou define o estilo. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Define a página que contém este cabeçalho. |
| [setTop](#setTop-double-) | define o Y superior destes cabeçalhos (para uso interno). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Obtém ou define o rótulo do usuário. |

### Heading {#Heading--}
```
public Heading()
```

Somente para uso interno

### Heading {#Heading-int-}
```
public Heading(int level)
```

Inicializa uma nova instância da classe Cell.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level |  | O nível dos cabeçalhos. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona o título com todos os segmentos.

**Returns:**
O objeto clonado

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona o título.

**Returns:**
O objeto clonado

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Obtém a página de destino.

**Returns:**
A página de destino.

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtém o nível.

**Returns:**
O nível do cabeçalho.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Obtém o número inicial do título.

**Returns:**
Valor: O startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Obtém ou define o estilo.

**Returns:**
O estilo do cabeçalho.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Obtém a página que contém este título.

**Returns:**
A página.

### getTop {#getTop--}
```
public double getTop()
```

Obtém o Y superior destes títulos (para uso interno).

**Returns:**
O valor Y superior

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Obtém ou define o rótulo do usuário.

**Returns:**
Objeto TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Obtém se o título deve ser numerado automaticamente.

**Returns:**
O IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Obtém se o título deve estar na lista de índice.

**Returns:**
O IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Define se o título deve ser numerado automaticamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Define a página de destino.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Define se o título deve estar na lista de índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

define o nível.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O nível do cabeçalho. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Obtém o número inicial do cabeçalho. Valor: O startNumber.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
define ou define o estilo.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Define a página que contém este cabeçalho.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

define o Y superior destes cabeçalhos (para uso interno).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | O valor Y superior |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Obtém ou define o rótulo do usuário.
