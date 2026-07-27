---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador cs (define o espaço de cores para operações sem traçado)"
type: docs
weight: 580
url: /pt/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Classe que representa o operador cs (define o espaço de cores para operações sem traçado)

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Construtor da classe operador. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Inicializa o operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getCommandName](#getCommandName--) | Obtém o nome do comando. |
| [getName](#getName--) | Obtém o nome do espaço de cores. |
| [setName](#setName-java.lang.String-) | Define o nome do espaço de cores. |
| [toCommand](#toCommand--) | Somente para uso interno! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Construtor da classe operador.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Inicializa o operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtém o nome do comando.

**Returns:**
valor String

### getName {#getName--}
```
public String getName()
```

Obtém o nome do espaço de cores.

**Returns:**
valor String

### setName {#setName-java.lang.String-}
Define o nome do espaço de cores.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Somente para uso interno!

**Returns:**
valor ICommand objeto ICommand
