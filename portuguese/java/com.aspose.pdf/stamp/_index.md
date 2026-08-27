---
title: "Carimbo"
linktitle: "Carimbo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe abstrata para vários tipos de carimbos que vêm como descendentes."
type: docs
weight: 4620
url: /pt/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Uma classe abstrata para vários tipos de carimbos que vêm como descendentes.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Obtém a margem inferior do carimbo. |
| [getHeight](#getHeight--) | Obtém a altura desejada do carimbo na página. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtém o alinhamento horizontal do carimbo na página. |
| [getLeftMargin](#getLeftMargin--) | Obtém a margem esquerda do carimbo. |
| [getOpacity](#getOpacity--) | Obtém um valor que indica a opacidade do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Obtém um valor que indica a opacidade do contorno do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Obtém um valor da largura do contorno do carimbo. Por padrão, o valor é 1.0. |
| [getRightMargin](#getRightMargin--) | Obtém a margem direita do carimbo. |
| [getRotate](#getRotate--) | Obtém a rotação do conteúdo do carimbo de acordo com os valores {@code Rotation}. Observação: esta propriedade serve para definir ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Obtém o ângulo de rotação do carimbo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário. |
| [getStampId](#getStampId--) | Obtém o ID do carimbo. |
| [getTopMargin](#getTopMargin--) | Obtém a margem superior do carimbo. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtém o alinhamento vertical do carimbo na página. |
| [getWidth](#getWidth--) | Obtém a largura desejada do carimbo na página. |
| [getXIndent](#getXIndent--) | Obtém a coordenada horizontal do carimbo, começando da esquerda. |
| [getYIndent](#getYIndent--) | Obtém a coordenada vertical do carimbo, começando da parte inferior. |
| [getZoom](#getZoom--) | Obtém o fator de zoom do carimbo. Permite dimensionar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. Definir esta propriedade altera ambas as propriedades ZoomX e ZoomY. Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX. |
| [getZoomX](#getZoomX--) | Obtém o fator de zoom horizontal do carimbo. Permite dimensionar o carimbo horizontalmente. |
| [getZoomY](#getZoomY--) | Obtém o fator de zoom vertical do carimbo. Permite dimensionar o carimbo verticalmente. |
| [isBackground](#isBackground--) | Obtém um valor booleano que indica se o conteúdo é carimbado como plano de fundo. Se o valor for true, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é false, o conteúdo do carimbo é colocado na parte superior. |
| [put](#put-com.aspose.pdf.Page-) | Adiciona carimbo na página. |
| [setBackground](#setBackground-boolean-) | Define um valor booleano que indica se o conteúdo é carimbado como plano de fundo. Se o valor for true, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é false, o conteúdo do carimbo é colocado na parte superior. |
| [setBottomMargin](#setBottomMargin-double-) | Define a margem inferior do carimbo. |
| [setHeight](#setHeight-double-) | Define a altura desejada do selo na página. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Define o alinhamento horizontal do selo na página. |
| [setLeftMargin](#setLeftMargin-double-) | Define a margem esquerda do selo. |
| [setOpacity](#setOpacity-double-) | Define um valor para indicar a opacidade do selo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Define um valor para indicar a opacidade do contorno do selo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Define um valor para a largura do contorno do selo. Por padrão, o valor é 1.0. |
| [setRightMargin](#setRightMargin-double-) | Define a margem direita do selo. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Define a rotação do conteúdo do selo de acordo com os valores {@code Rotation}. Observação: Esta propriedade serve para ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Define o ângulo de rotação do selo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário. |
| [setStampId](#setStampId-int-) | Define o Id do selo. |
| [setTopMargin](#setTopMargin-double-) | Define a margem superior do selo. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Define o alinhamento vertical do selo na página. |
| [setWidth](#setWidth-double-) | Define a largura desejada do selo na página. |
| [setXIndent](#setXIndent-double-) | Define a coordenada horizontal do selo, começando da esquerda. |
| [setYIndent](#setYIndent-double-) | Define a coordenada vertical do selo, começando de baixo. |
| [setZoom](#setZoom-double-) | Obtém o fator de zoom do carimbo. Permite dimensionar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. Definir esta propriedade altera ambas as propriedades ZoomX e ZoomY. Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX. |
| [setZoomX](#setZoomX-double-) | Define o fator de zoom horizontal do selo. Permite dimensionar o selo horizontalmente. |
| [setZoomY](#setZoomY-double-) | Define o fator de zoom vertical do selo. Permite dimensionar o selo verticalmente. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtém a margem inferior do carimbo.

**Returns:**
valor double

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém a altura desejada do carimbo na página.

**Returns:**
valor double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtém o alinhamento horizontal do carimbo na página.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtém a margem esquerda do carimbo.

**Returns:**
valor double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtém um valor que indica a opacidade do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0.

**Returns:**
valor double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Obtém um valor que indica a opacidade do contorno do carimbo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0.

**Returns:**
valor double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Obtém um valor da largura do contorno do carimbo. Por padrão, o valor é 1.0.

**Returns:**
valor double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtém a margem direita do carimbo.

**Returns:**
valor double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Obtém a rotação do conteúdo do carimbo de acordo com os valores {@code Rotation}. Observação: esta propriedade serve para definir ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None.

**Returns:**
Valor de rotação @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Obtém o ângulo de rotação do carimbo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário.

**Returns:**
valor double

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtém o ID do carimbo.

**Returns:**
Identificador do selo.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtém a margem superior do carimbo.

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtém o alinhamento vertical do carimbo na página.

**Returns:**
Valor de VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura desejada do carimbo na página.

**Returns:**
valor double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtém a coordenada horizontal do carimbo, começando da esquerda.

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtém a coordenada vertical do carimbo, começando da parte inferior.

**Returns:**
valor double

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtém o fator de zoom do carimbo. Permite dimensionar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. Definir esta propriedade altera ambas as propriedades ZoomX e ZoomY. Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX.

**Returns:**
valor double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Obtém o fator de zoom horizontal do carimbo. Permite dimensionar o carimbo horizontalmente.

**Returns:**
valor double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Obtém o fator de zoom vertical do carimbo. Permite dimensionar o carimbo verticalmente.

**Returns:**
valor double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtém um valor booleano que indica se o conteúdo é carimbado como plano de fundo. Se o valor for true, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é false, o conteúdo do carimbo é colocado na parte superior.

**Returns:**
valor booleano

### put {#put-com.aspose.pdf.Page-}
Adiciona carimbo na página.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Define um valor booleano que indica se o conteúdo é carimbado como plano de fundo. Se o valor for true, o conteúdo do carimbo é colocado na parte inferior. Por padrão, o valor é false, o conteúdo do carimbo é colocado na parte superior.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Define a margem inferior do carimbo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Define a altura desejada do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Define o alinhamento horizontal do selo na página.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Define a margem esquerda do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Define um valor para indicar a opacidade do selo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Define um valor para indicar a opacidade do contorno do selo. O valor varia de 0.0 a 1.0. Por padrão, o valor é 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Define um valor para a largura do contorno do selo. Por padrão, o valor é 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Define a margem direita do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Define a rotação do conteúdo do selo de acordo com os valores {@code Rotation}. Observação: Esta propriedade serve para ângulos que são múltiplos de 90 graus (0, 90, 180, 270 graus). Para definir um ângulo arbitrário, use a propriedade RotateAngle. Se o ângulo definido por ArbitraryAngle não for múltiplo de 90, então a propriedade Rotate retorna Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Define o ângulo de rotação do selo em graus. Esta propriedade permite definir um ângulo de rotação arbitrário.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | ângulo de rotação |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Define o Id do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Novo valor do ID do selo. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Define a margem superior do selo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Define o alinhamento vertical do selo na página.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura desejada do selo na página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Define a coordenada horizontal do selo, começando da esquerda.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Define a coordenada vertical do selo, começando de baixo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Obtém o fator de zoom do carimbo. Permite dimensionar o carimbo. Observe que o par de propriedades ZoomX e ZoomY permite definir o fator de zoom para cada eixo separadamente. Definir esta propriedade altera ambas as propriedades ZoomX e ZoomY. Se ZoomX e ZoomY forem diferentes, então a propriedade Zoom retorna o valor de ZoomX.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Define o fator de zoom horizontal do selo. Permite dimensionar o selo horizontalmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Define o fator de zoom vertical do selo. Permite dimensionar o selo verticalmente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
