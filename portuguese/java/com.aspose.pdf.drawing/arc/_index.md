---
title: "Arco"
linktitle: "Arco"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um arco."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Representa um arco.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Arc](#Arc--) | Somente para uso interno |
| [Arc](#Arc-double-double-double-double-double-) | Inicializa uma nova instância da classe {@code Arc}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se o item se encaixa nas dimensões do contêiner fornecidas (inclusivo). |
| [getAlpha](#getAlpha--) | Obtém o valor float que indica o grau do ângulo inicial do arco. |
| [getBeta](#getBeta--) | Obtém o valor float que indica o grau do ângulo final do arco. |
| [getPosX](#getPosX--) | Obtém o valor float que indica a coordenada x do centro do arco. |
| [getPosY](#getPosY--) | Obtém o valor float que indica a coordenada y do centro do arco. |
| [getRadius](#getRadius--) | Obtém o valor float que indica o raio do arco. |
| [setAlpha](#setAlpha-double-) | Define o valor float que indica o grau do ângulo inicial do arco. |
| [setBeta](#setBeta-double-) | Define o valor float que indica o grau do ângulo final do arco. |
| [setPosX](#setPosX-double-) | Define o valor float que indica a coordenada x do centro do arco. |
| [setPosY](#setPosY-double-) | Define o valor float que indica a coordenada y do centro do arco. |
| [setRadius](#setRadius-double-) | Define o valor float que indica o raio do arco. |

### Arc {#Arc--}
```
public Arc()
```

Somente para uso interno

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Inicializa uma nova instância da classe {@code Arc}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| posX |  | A coordenada x do ponto central do arco. |
| posY |  | A coordenada y do ponto central do arco. |
| raio |  | O valor do raio do arco. |
| alpha |  | O valor do ângulo inicial do arco. |
| beta |  | O valor do ângulo final do arco. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Obtém o valor float que indica o grau do ângulo inicial do arco.

**Returns:**
valor alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

Obtém o valor float que indica o grau do ângulo final do arco.

**Returns:**
valor beta

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

Obtém o valor float que indica o raio do arco.

**Returns:**
valor que indica o raio do arco.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Define o valor float que indica o grau do ângulo inicial do arco.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Define o valor float que indica o grau do ângulo final do arco.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor beta |

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

Define o valor float que indica o raio do arco.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | que indica o raio do arco. |
