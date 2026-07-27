---
title: "Graph"
linktitle: "Graph"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o parágrafo gerador de gráficos."
type: docs
weight: 70
url: /pt/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Representa o parágrafo gerador de gráficos.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Graph](#Graph--) | Somente para uso interno |
| [Graph](#Graph-double-double-) | Inicializa uma nova instância da classe {@link Graph}. |
| [Graph](#Graph-float-float-) | Inicializa uma nova instância da classe {@code Graph}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona o gráfico. |
| [getBorder](#getBorder--) | Obtém a borda. |
| [getGraphInfo](#getGraphInfo--) | Obtém um objeto {@code GraphInfo} que indica as informações do gráfico, como cor, largura da linha, etc. |
| [getHeight](#getHeight--) | Obtém o valor float que indica a altura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphHeight=\"10cm\" ou GraphHeight=\"5inch\". |
| [getLeft](#getLeft--) | Obtém a coordenada esquerda da tabela. |
| [getShapes](#getShapes--) | Obtém uma coleção que indica todas as formas no gráfico. |
| [getTitle](#getTitle--) | Obtém o valor string que indica o título do gráfico. |
| [getTop](#getTop--) | Obtém a coordenada superior da tabela. |
| [getWidth](#getWidth--) | Obtém o valor float que indica a largura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphWidth=\"10cm\" ou GraphWidth=\"5inch\". |
| [isChangePosition](#isChangePosition--) | Obtém se altera a posição atual após processar o parágrafo (padrão true). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Define a borda. |
| [setChangePosition](#setChangePosition-boolean-) | Define se altera a posição atual após processar o parágrafo (padrão true). |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Obtém ou define um objeto {@code GraphInfo} que indica as informações do gráfico, como cor, largura da linha, etc. |
| [setHeight](#setHeight-double-) | Define o valor float que indica a altura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphHeight=\"10cm\" ou GraphHeight=\"5inch\". |
| [setLeft](#setLeft-double-) | Define a coordenada esquerda da tabela. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Define uma coleção que indica todas as formas no gráfico. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Define o valor string que indica o título do gráfico. |
| [setTop](#setTop-double-) | Define a coordenada superior da tabela. |
| [setWidth](#setWidth-double-) | Define o valor float que indica a largura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphWidth=\"10cm\" ou GraphWidth=\"5inch\". |

### Graph {#Graph--}
```
public Graph()
```

Somente para uso interno

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Inicializa uma nova instância da classe {@link Graph}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | A largura do gráfico. |
| altura |  | A altura do gráfico. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Inicializa uma nova instância da classe {@code Graph}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | A largura do gráfico. |
| altura |  | A altura do gráfico. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona o gráfico.

**Returns:**
O objeto clonado

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtém a borda.

**Returns:**
elemento BorderInfo

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtém um objeto {@code GraphInfo} que indica as informações do gráfico, como cor, largura da linha, etc.

**Returns:**
objeto GraphInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém o valor float que indica a altura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphHeight=\"10cm\" ou GraphHeight=\"5inch\".

**Returns:**
valor que indica a altura do gráfico.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtém a coordenada esquerda da tabela.

**Returns:**
coordenada esquerda da tabela.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Obtém uma coleção que indica todas as formas no gráfico.

**Returns:**
BoundsCheckableList de Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtém o valor string que indica o título do gráfico.

**Returns:**
título do gráfico.

### getTop {#getTop--}
```
public double getTop()
```

Obtém a coordenada superior da tabela.

**Returns:**
a coordenada superior da tabela.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém o valor float que indica a largura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphWidth=\"10cm\" ou GraphWidth=\"5inch\".

**Returns:**
valor float que indica a largura do gráfico.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Obtém se altera a posição atual após processar o parágrafo (padrão true).

**Returns:**
valor booleano

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Define a borda.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Define se altera a posição atual após processar o parágrafo (padrão true).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Obtém ou define um objeto {@code GraphInfo} que indica as informações do gráfico, como cor, largura da linha, etc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Define o valor float que indica a altura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphHeight=\"10cm\" ou GraphHeight=\"5inch\".

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | que indica a altura do gráfico. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Define a coordenada esquerda da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | coordenada esquerda da tabela. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Define uma coleção que indica todas as formas no gráfico.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Define o valor string que indica o título do gráfico.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Define a coordenada superior da tabela.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | a coordenada superior da tabela. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define o valor float que indica a largura do gráfico. A unidade é ponto. No XML, a unidade padrão é ponto, mas cm e polegada também são suportados. Por exemplo, GraphWidth=\"10cm\" ou GraphWidth=\"5inch\".

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float que indica a largura do gráfico. |
