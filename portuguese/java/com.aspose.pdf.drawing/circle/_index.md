---
title: "Círculo"
linktitle: "Círculo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um círculo."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Representa um círculo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Circle](#Circle--) | Somente para uso interno |
| [Circle](#Circle-float-float-float-) | Inicializa uma nova instância da classe {@code Circle}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getPosX](#getPosX--) | Obtém o valor float que indica a coordenada x do centro do arco. |
| [getPosY](#getPosY--) | Obtém o valor float que indica a coordenada y do centro do arco. |
| [getRadius](#getRadius--) | Obtém o valor float que indica o raio do círculo. |
| [setPosX](#setPosX-double-) | Define o valor float que indica a coordenada x do centro do arco. |
| [setPosY](#setPosY-double-) | Define o valor float que indica a coordenada y do centro do arco. |
| [setRadius](#setRadius-double-) | Define o valor float que indica o raio do círculo. |

### Circle {#Circle--}
```
public Circle()
```

Somente para uso interno

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Inicializa uma nova instância da classe {@code Circle}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| posX |  | A coordenada x do centro do círculo. |
| posY |  | A coordenada y do centro do círculo. |
| raio |  | O raio do círculo. |

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

### getPosX {#getPosX--}
```
public double getPosX()
```

Obtém o valor float que indica a coordenada x do centro do arco.

**Returns:**
coordenada x do centro do arco.

### getPosY {#getPosY--}
```
public double getPosY()
```

Obtém o valor float que indica a coordenada y do centro do arco.

**Returns:**
coordenada y do centro do arco.

### getRadius {#getRadius--}
```
public double getRadius()
```

Obtém o valor float que indica o raio do círculo.

**Returns:**
valor que indica o raio do círculo.

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Define o valor float que indica a coordenada x do centro do arco.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | coordenada x do centro do arco. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Define o valor float que indica a coordenada y do centro do arco.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | coordenada y do centro do arco. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Define o valor float que indica o raio do círculo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | que indica o raio do círculo. |
