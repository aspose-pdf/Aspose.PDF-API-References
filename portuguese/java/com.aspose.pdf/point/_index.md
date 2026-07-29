---
title: "Ponto"
linktitle: "Ponto"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um ponto com coordenadas fracionárias."
type: docs
weight: 3870
url: /pt/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Representa um ponto com coordenadas fracionárias.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Point](#Point-double-double-) | Inicializa uma nova instância do {@code Point}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Calcula a distância entre dois pontos. |
| [getTrivial](#getTrivial--) | Obtém ponto com coordenadas zero. |
| [getX](#getX--) | Obtém o valor da coordenada X. |
| [getY](#getY--) | Obtém o valor da coordenada Y. |
| [setX](#setX-double-) | Define o valor da coordenada X. |
| [setY](#setY-double-) | Define o valor da coordenada Y. |
| [toPoint](#toPoint--) | Converte o ponto em um objeto java.awt.geom.Point2D.Float. |
| [toString](#toString--) | Retorna a representação em string do ponto atual. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Inicializa uma nova instância do {@code Point}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Valor da coordenada x. |
| y |  | Valor da coordenada y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Calcula a distância entre dois pontos.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Obtém ponto com coordenadas zero.

**Returns:**
Objeto Point

### getX {#getX--}
```
public double getX()
```

Obtém o valor da coordenada X.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Obtém o valor da coordenada Y.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Define o valor da coordenada X.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Define o valor da coordenada Y.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Converte o ponto em um objeto java.awt.geom.Point2D.Float.

**Returns:**
Estrutura Float.

### toString {#toString--}
```
public String toString()
```

Retorna a representação em string do ponto atual.

**Returns:**
String que representa o ponto atual.
