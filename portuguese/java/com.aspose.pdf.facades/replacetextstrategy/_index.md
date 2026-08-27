---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe contém parâmetros que definem o comportamento do PdfContentEditor quando a operação ReplaceText é executada."
type: docs
weight: 650
url: /pt/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Esta classe contém parâmetros que definem o comportamento do PdfContentEditor quando a operação ReplaceText é executada.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Ação executada quando nenhuma fonte apropriada é encontrada para o texto alterado (Lançar exceção / Substituir por outra fonte / Substituir de qualquer forma). |
| [getReplaceScope](#getReplaceScope--) | Escopo da operação de substituição (substituir a primeira ocorrência ou substituir todas as ocorrências). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Se false, a string a ser encontrada é um texto simples. Se true, a string a ser encontrada é uma expressão regular. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Ação executada quando nenhuma fonte apropriada é encontrada para o texto alterado (Lançar exceção / Substituir por outra fonte / Substituir de qualquer forma). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Se false, a string a ser encontrada é um texto simples. Se true, a string a ser encontrada é uma expressão regular. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Escopo da operação de substituição (substituir a primeira ocorrência ou substituir todas as ocorrências). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Ação executada quando nenhuma fonte apropriada é encontrada para o texto alterado (Lançar exceção / Substituir por outra fonte / Substituir de qualquer forma).

**Returns:**
Valor de NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Escopo da operação de substituição (substituir a primeira ocorrência ou substituir todas as ocorrências).

**Returns:**
Elemento Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Se false, a string a ser encontrada é um texto simples. Se true, a string a ser encontrada é uma expressão regular.

**Returns:**
valor booleano

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Ação executada quando nenhuma fonte apropriada é encontrada para o texto alterado (Lançar exceção / Substituir por outra fonte / Substituir de qualquer forma).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Se false, a string a ser encontrada é um texto simples. Se true, a string a ser encontrada é uma expressão regular.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Escopo da operação de substituição (substituir a primeira ocorrência ou substituir todas as ocorrências).
