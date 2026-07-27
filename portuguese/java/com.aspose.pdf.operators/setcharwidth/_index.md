---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador d0 (define a largura do glifo)."
type: docs
weight: 510
url: /pt/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Classe que representa o operador d0 (define a largura do glifo).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Construtor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getWx](#getWx--) | Deslocamento horizontal da coordenada do glifo. |
| [getWy](#getWy--) | Deslocamento vertical da coordenada do glifo. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Construtor.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| wx |  | Deslocamento horizontal do glifo. |
| wy |  | Deslocamento vertical do glifo. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getWx {#getWx--}
```
public double getWx()
```

Deslocamento horizontal da coordenada do glifo.

**Returns:**
valor double

### getWy {#getWy--}
```
public double getWy()
```

Deslocamento vertical da coordenada do glifo.

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
