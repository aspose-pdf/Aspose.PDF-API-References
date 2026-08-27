---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador cm (concatenar matriz à matriz de transformação atual)."
type: docs
weight: 140
url: /pt/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Classe que representa o operador cm (concatenar matriz à matriz de transformação atual).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Construtor da classe operador. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Construtor da classe operador. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Inicializa o operador por matriz. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getMatrix](#getMatrix--) | Argumento de matriz do operador. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumento de matriz do operador. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Construtor da classe operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a |  | Coeficiente A |
| b |  | Coeficiente B |
| c |  | Coeficiente C |
| d |  | Coeficiente D |
| e |  | Coeficiente E |
| f |  | Coeficiente F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Construtor da classe operador.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
Inicializa o operador por matriz.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argumento de matriz do operador.

**Returns:**
Objeto Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argumento de matriz do operador.

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
