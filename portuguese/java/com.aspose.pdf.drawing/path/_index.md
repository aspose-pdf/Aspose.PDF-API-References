---
title: "Path"
linktitle: "Path"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um arco."
type: docs
weight: 100
url: /pt/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Representa um arco.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Path](#Path--) | Inicializa uma nova instância da classe {@code Path}. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Inicializa uma nova instância da classe {@code Path}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getShapes](#getShapes--) | <p> Obtém ou define a coleção de formas. </p> |
| [getShapesInternal](#getShapesInternal--) | Obtém ou define a coleção de formas. |

### Path {#Path--}
```
public Path()
```

Inicializa uma nova instância da classe {@code Path}.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Inicializa uma nova instância da classe {@code Path}.

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Obtém ou define a coleção de formas. </p>

**Returns:**
{@code java.util.List<Shape> }objeto

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Obtém ou define a coleção de formas.

**Returns:**
objeto interno
