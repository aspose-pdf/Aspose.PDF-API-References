---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore cs (imposta lo spazio colore per operazioni non di tracciatura)"
type: docs
weight: 580
url: /it/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Classe che rappresenta l'operatore cs (imposta lo spazio colore per operazioni non di tracciatura)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Costruttore per la classe operatore. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Inizializza l'operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getCommandName](#getCommandName--) | Ottiene il nome del comando. |
| [getName](#getName--) | Ottiene il nome dello spazio colore. |
| [setName](#setName-java.lang.String-) | Imposta il nome dello spazio colore. |
| [toCommand](#toCommand--) | Solo per uso interno! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Costruttore per la classe operatore.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Inizializza l'operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Ottiene il nome del comando.

**Returns:**
valore String

### getName {#getName--}
```
public String getName()
```

Ottiene il nome dello spazio colore.

**Returns:**
valore String

### setName {#setName-java.lang.String-}
Imposta il nome dello spazio colore.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand
