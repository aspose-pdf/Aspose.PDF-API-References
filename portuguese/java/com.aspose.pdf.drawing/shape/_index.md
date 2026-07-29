---
title: "Shape"
linktitle: "Shape"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa forma - o objeto gráfico base."
type: docs
weight: 130
url: /pt/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Representa forma - o objeto gráfico base.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Shape](#Shape--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getGraphInfo](#getGraphInfo--) | Obtém objeto que indica as informações do gráfico, como cor, largura da linha, etc. |
| [getText](#getText--) | Obtém ou define um texto para a forma |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Define objeto que indica as informações do gráfico, como cor, largura da linha, etc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Obtém ou define um texto para a forma |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Verdadeiro se couber; caso contrário, falso.

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtém objeto que indica as informações do gráfico, como cor, largura da linha, etc.

**Returns:**
objeto que indica as informações do gráfico.

### getText {#getText--}
```
public TextFragment getText()
```

Obtém ou define um texto para a forma

**Returns:**
objeto TextFragment

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Define objeto que indica as informações do gráfico, como cor, largura da linha, etc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Obtém ou define um texto para a forma
