---
title: "Operator"
linktitle: "Operator"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe abstrata que representa o operador."
type: docs
weight: 3180
url: /pt/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Classe abstrata que representa o operador.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Somente para uso interno! |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita o visitante IOperatorSelector que fornece o processamento de operadores. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Cria um operador pelo nome da instância com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Compara esta instância com o objeto fornecido. |
| [getCommand](#getCommand--) | Obtém o comando |
| [getCommandName](#getCommandName--) | Obtém o nome do operador. |
| [getIndex](#getIndex--) | Obtém o índice do operador na lista de operadores da página. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Determina se o operador é aquele responsável pela saída de texto (Tj, TJ, etc). |
| [setIndex](#setIndex-int-) | Defina o índice do Operador na lista de operadores da página. |
| [toString](#toString--) | Traduz o comando e os parâmetros para a representação em string. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Compara esta instância com o objeto fornecido. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Somente para uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita o visitante IOperatorSelector que fornece o processamento de operadores.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Cria um operador pelo nome da instância com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Compara esta instância com o objeto fornecido.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Obtém o comando

**Returns:**
Objeto ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtém o nome do operador.

**Returns:**
valor String

### getIndex {#getIndex--}
```
public int getIndex()
```

Obtém o índice do operador na lista de operadores da página.

**Returns:**
valor int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Determina se o operador é aquele responsável pela saída de texto (Tj, TJ, etc).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Defina o índice do Operador na lista de operadores da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### toString {#toString--}
```
public String toString()
```

Traduz o comando e os parâmetros para a representação em string.

**Returns:**
Texto do Operador

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Compara esta instância com o objeto fornecido.
