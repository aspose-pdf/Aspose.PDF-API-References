---
title: "Line"
linktitle: "Line"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma linha."
type: docs
weight: 90
url: /pt/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Representa uma linha.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Line](#Line--) | Somente para uso interno |
| [Line](#Line-float:A-) | Inicializa uma nova instância da classe {@code Line}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getPositionArray](#getPositionArray--) | Obtém objeto que indica o array de posições. O array é composto por coordenadas de cada ponto de controle da linha. diretamente. |
| [setPositionArray](#setPositionArray-float:A-) | Define objeto que indica o array de posições. O array é composto por coordenadas de cada ponto de controle da linha. diretamente. |

### Line {#Line--}
```
public Line()
```

Somente para uso interno

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Inicializa uma nova instância da classe {@code Line}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| positionArray |  | O array de posições da linha. |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Obtém objeto que indica o array de posições. O array é composto por coordenadas de cada ponto de controle da linha. diretamente.

**Returns:**
que indica o array de posições.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Define objeto que indica o array de posições. O array é composto por coordenadas de cada ponto de controle da linha. diretamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | que indica o array de posições. |
