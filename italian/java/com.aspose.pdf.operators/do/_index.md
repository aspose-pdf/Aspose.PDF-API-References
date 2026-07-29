---
title: "Do"
linktitle: "Do"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore Do (Invoca XObject)."
type: docs
weight: 180
url: /it/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Classe che rappresenta l'operatore Do (Invoca XObject).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Do](#Do--) | Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti. |
| [Do](#Do-java.lang.String-) | Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getCommandName](#getCommandName--) | Restituisce il nome del comando |
| [getName](#getName--) | Ottiene il nome dell'argomento XObject dell'operatore. |
| [setName](#setName-java.lang.String-) | Imposta il nome dell'argomento XObject dell'operatore. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### Do {#Do--}
```
public Do()
```

Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti.

### Do {#Do-java.lang.String-}
Costruisce un nuovo operatore Do. Usato per recuperare tutti gli operatori Do, cioè senza controllare i nomi dei loro argomenti.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Restituisce il nome del comando

**Returns:**
valore String

### getName {#getName--}
```
public String getName()
```

Ottiene il nome dell'argomento XObject dell'operatore.

**Returns:**
valore String

### setName {#setName-java.lang.String-}
Imposta il nome dell'argomento XObject dell'operatore.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.
