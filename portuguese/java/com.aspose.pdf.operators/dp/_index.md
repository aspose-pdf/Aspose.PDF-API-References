---
title: "DP"
linktitle: "DP"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador DP (designar ponto de conteúdo marcado)."
type: docs
weight: 190
url: /pt/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Classe que representa o operador DP (designar ponto de conteúdo marcado).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Construtor da classe operador. |
| [DP](#DP-java.lang.String-) | Inicializa o operador. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Obtém o dicionário de propriedades |
| [getTag](#getTag--) | Obtém a etiqueta de conteúdo marcado |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Define o dicionário de propriedades |
| [setTag](#setTag-java.lang.String-) | Define a etiqueta de conteúdo marcado |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Construtor da classe operador.

### DP {#DP-java.lang.String-}
Inicializa o operador.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Obtém o dicionário de propriedades

**Returns:**
IPdfDictionary value

### getTag {#getTag--}
```
public String getTag()
```

Obtém a etiqueta de conteúdo marcado

**Returns:**
valor String

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Define o dicionário de propriedades

### setTag {#setTag-java.lang.String-}
Define a etiqueta de conteúdo marcado

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
