---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa a borda para elementos gráficos."
type: docs
weight: 370
url: /pt/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Esta classe representa a borda para elementos gráficos.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Inicializa uma nova instância da classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Inicializa uma nova instância da classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Inicializa uma nova instância da classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Inicializa uma nova instância da classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Inicializa uma nova instância da classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Inicializa uma nova instância da classe {@code BorderInfo}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Clona um novo objeto BorderInfo. |
| [getBottom](#getBottom--) | Obtém o objeto que indica a parte inferior da borda. |
| [getLeft](#getLeft--) | Obtém o objeto {@code GraphInfo} que indica o lado esquerdo da borda. |
| [getRight](#getRight--) | Obtém o objeto {@code GraphInfo} que indica o lado direito da borda. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Obtém o raio da borda arredondada. |
| [getTop](#getTop--) | Obtém o objeto {@code GraphInfo} que indica a borda superior. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Define o objeto que indica a parte inferior da borda. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Define o objeto {@code GraphInfo} que indica o lado esquerdo da borda. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Define o objeto {@code GraphInfo} que indica o lado direito da borda. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Define o raio da borda arredondada. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Define o objeto {@code GraphInfo} que indica a parte superior da borda. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Inicializa uma nova instância da classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Inicializa uma nova instância da classe {@code BorderInfo}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| borderSide |  | Indica as informações dos lados da borda. Por exemplo: (BorderSide.Left \" | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Inicializa uma nova instância da classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Inicializa uma nova instância da classe {@code BorderInfo}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| borderSide |  | Indica as informações dos lados da borda. Por exemplo: (BorderSide.Left \" | BorderSide.Top). |
| borderWidth |  | A largura da borda. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Inicializa uma nova instância da classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Inicializa uma nova instância da classe {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona um novo objeto BorderInfo.

**Returns:**
O novo objeto BorderInfo.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Obtém o objeto que indica a parte inferior da borda.

**Returns:**
inferior

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Obtém o objeto {@code GraphInfo} que indica o lado esquerdo da borda.

**Returns:**
objeto que indica o lado esquerdo da borda.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Obtém o objeto {@code GraphInfo} que indica o lado direito da borda.

**Returns:**
objeto que indica o lado direito da borda.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Obtém o raio da borda arredondada.

**Returns:**
valor

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Obtém o objeto {@code GraphInfo} que indica a borda superior.

**Returns:**
objeto que indica a borda superior

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Define o objeto que indica a parte inferior da borda.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Define o objeto {@code GraphInfo} que indica o lado esquerdo da borda.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Define o objeto {@code GraphInfo} que indica o lado direito da borda.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Define o raio da borda arredondada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Define o objeto {@code GraphInfo} que indica a parte superior da borda.
