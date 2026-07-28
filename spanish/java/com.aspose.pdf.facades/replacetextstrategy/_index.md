---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación ReplaceText."
type: docs
weight: 650
url: /es/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación ReplaceText.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Acción que se realiza cuando no se encuentra una fuente adecuada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos). |
| [getReplaceScope](#getReplaceScope--) | Ámbito de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Acción que se realiza cuando no se encuentra una fuente adecuada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Ámbito de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Acción que se realiza cuando no se encuentra una fuente adecuada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos).

**Returns:**
Valor de NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Ámbito de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias).

**Returns:**
Elemento Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular.

**Returns:**
valor booleano

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Acción que se realiza cuando no se encuentra una fuente adecuada para el texto modificado (Lanzar excepción / Sustituir por otra fuente / Reemplazar de todos modos).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Si es false, la cadena a buscar es un texto simple. Si es true, la cadena a buscar es una expresión regular.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Ámbito de la operación de reemplazo (reemplazar la primera ocurrencia o reemplazar todas las ocurrencias).
