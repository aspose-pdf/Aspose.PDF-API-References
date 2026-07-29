---
title: "Do"
linktitle: "Do"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador Do (Invocar XObject)."
type: docs
weight: 180
url: /pt/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Classe que representa o operador Do (Invocar XObject).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Do](#Do--) | Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos. |
| [Do](#Do-java.lang.String-) | Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getCommandName](#getCommandName--) | Obtém o nome do comando |
| [getName](#getName--) | Obtém o nome do argumento XObject do operador. |
| [setName](#setName-java.lang.String-) | Define o nome do argumento XObject do operador. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### Do {#Do--}
```
public Do()
```

Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos.

### Do {#Do-java.lang.String-}
Constrói um novo operador Do. Usado para recuperar todos os operadores Do, ou seja, sem verificar os nomes de seus argumentos.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtém o nome do comando

**Returns:**
valor String

### getName {#getName--}
```
public String getName()
```

Obtém o nome do argumento XObject do operador.

**Returns:**
valor String

### setName {#setName-java.lang.String-}
Define o nome do argumento XObject do operador.

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
Representação textual do operador.
