---
title: "Curve"
linktitle: "Curve"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma curva Bézier."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Representa uma curva Bézier.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Curve](#Curve--) | Somente para uso interno |
| [Curve](#Curve-float:A-) | Inicializa uma nova instância da classe {@code Curve}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getPositionArray](#getPositionArray--) | Obtém um array de posições float. |
| [setPositionArray](#setPositionArray-float:A-) | Define um array de posições float. |

### Curve {#Curve--}
```
public Curve()
```

Somente para uso interno

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Inicializa uma nova instância da classe {@code Curve}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| positionArray |  | O array de posições dos pontos de controle da curva. Devem existir quatro pontos de controle, portanto o comprimento do array deve ser oito. |

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

Obtém um array de posições float.

**Returns:**
array float[]

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Define um array de posições float.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array float[] |
