---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador d1 (define o glifo e a caixa delimitadora)."
type: docs
weight: 520
url: /pt/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Classe que representa o operador d1 (define o glifo e a caixa delimitadora).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Inicializa o operador SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getLlx](#getLlx--) | Coordenada horizontal inferior esquerda do retângulo delimitador. |
| [getLly](#getLly--) | Coordenada vertical inferior esquerda do retângulo delimitador. |
| [getUrx](#getUrx--) | Coordenada horizontal superior direita do retângulo delimitador. |
| [getUry](#getUry--) | Coordenada vertical superior direita do retângulo delimitador. |
| [getWx](#getWx--) | Deslocamento horizontal do glifo. |
| [getWy](#getWy--) | Deslocamento vertical do glifo. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Inicializa o operador SetCharWidthBoundingBox.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| wx |  | Denota o deslocamento horizontal nas coordenadas do glifo. |
| wy |  | Denota o deslocamento vertical nas coordenadas do glifo. Deve ser 0. |
| llx |  | Denota a coordenada X do canto inferior esquerdo. |
| lly |  | Denota a coordenada Y do canto inferior esquerdo. |
| urx |  | Denota a coordenada X do canto superior direito. |
| ury |  | Denota a coordenada Y do canto superior direito. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getLlx {#getLlx--}
```
public double getLlx()
```

Coordenada horizontal inferior esquerda do retângulo delimitador.

**Returns:**
valor double

### getLly {#getLly--}
```
public double getLly()
```

Coordenada vertical inferior esquerda do retângulo delimitador.

**Returns:**
valor double

### getUrx {#getUrx--}
```
public double getUrx()
```

Coordenada horizontal superior direita do retângulo delimitador.

**Returns:**
valor double

### getUry {#getUry--}
```
public double getUry()
```

Coordenada vertical superior direita do retângulo delimitador.

**Returns:**
valor double

### getWx {#getWx--}
```
public double getWx()
```

Deslocamento horizontal do glifo.

**Returns:**
valor double

### getWy {#getWy--}
```
public double getWy()
```

Deslocamento vertical do glifo.

**Returns:**
valor double

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Somente para uso interno!

**Returns:**
valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual da representação
