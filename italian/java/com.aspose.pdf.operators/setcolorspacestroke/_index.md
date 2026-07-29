---
title: "SetColorSpaceStroke"
linktitle: "SetColorSpaceStroke"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore CS (imposta il colore per operazioni di tracciatura)."
type: docs
weight: 590
url: /it/java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

Classe che rappresenta l'operatore CS (imposta il colore per operazioni di tracciatura).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | Costruttore per la classe operatore. |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | Inizializza l'operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta un oggetto visitor per elaborare l'operatore. |
| [getName](#getName--) | Ottiene il nome dello spazio colore. |
| [setName](#setName-java.lang.String-) | Imposta il nome dello spazio colore. |
| [toCommand](#toCommand--) | Solo per uso interno! |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
Costruttore per la classe operatore.

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
Inizializza l'operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta un oggetto visitor per elaborare l'operatore.

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
