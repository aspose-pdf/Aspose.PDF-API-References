---
title: "Operator"
linktitle: "Operator"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe astratta che rappresenta l'operatore."
type: docs
weight: 3180
url: /it/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Classe astratta che rappresenta l'operatore.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Solo per uso interno! |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta il visitatore IOperatorSelector che fornisce l'elaborazione degli operatori. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Crea un operatore in base al nome dell'istanza com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Confronta questa istanza con l'oggetto fornito. |
| [getCommand](#getCommand--) | Ottiene il comando |
| [getCommandName](#getCommandName--) | Ottiene il nome dell'operatore. |
| [getIndex](#getIndex--) | Ottieni l'indice dell'operatore nell'elenco degli operatori della pagina. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Determina se l'operatore è un operatore responsabile dell'output di testo (Tj, TJ, ecc). |
| [setIndex](#setIndex-int-) | Imposta l'indice dell'operatore nell'elenco degli operatori della pagina. |
| [toString](#toString--) | Traduce il comando e i parametri in una rappresentazione stringa. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Confronta questa istanza con l'oggetto fornito. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Solo per uso interno!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta il visitatore IOperatorSelector che fornisce l'elaborazione degli operatori.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Crea un operatore in base al nome dell'istanza com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Confronta questa istanza con l'oggetto fornito.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Ottiene il comando

**Returns:**
Oggetto ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Ottiene il nome dell'operatore.

**Returns:**
valore String

### getIndex {#getIndex--}
```
public int getIndex()
```

Ottieni l'indice dell'operatore nell'elenco degli operatori della pagina.

**Returns:**
valore int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Determina se l'operatore è un operatore responsabile dell'output di testo (Tj, TJ, ecc).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Imposta l'indice dell'operatore nell'elenco degli operatori della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### toString {#toString--}
```
public String toString()
```

Traduce il comando e i parametri in una rappresentazione stringa.

**Returns:**
Testo dell'operatore

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Confronta questa istanza con l'oggetto fornito.
