---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador Tf (define a fonte e o tamanho do texto)."
type: docs
weight: 470
url: /pt/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Classe que representa o operador Tf (define a fonte e o tamanho do texto).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Construtor da classe operador. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Construtor para programa de escrita. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getName](#getName--) | Obtém o nome da fonte. |
| [getSize](#getSize--) | Obtém o tamanho do texto. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Construtor da classe operador.

### SelectFont {#SelectFont-java.lang.String-double-}
Construtor para programa de escrita.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getName {#getName--}
```
public String getName()
```

Obtém o nome da fonte.

**Returns:**
valor String

### getSize {#getSize--}
```
public double getSize()
```

Obtém o tamanho do texto.

**Returns:**
valor double

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.
