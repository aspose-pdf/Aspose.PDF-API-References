---
title: "DP"
linktitle: "DP"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore DP (designa il punto di contenuto marcato)."
type: docs
weight: 190
url: /it/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Classe che rappresenta l'operatore DP (designa il punto di contenuto marcato).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Costruttore per la classe operatore. |
| [DP](#DP-java.lang.String-) | Inizializza l'operatore. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Ottiene il dizionario delle proprietà |
| [getTag](#getTag--) | Ottiene il tag di contenuto marcato |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Imposta il dizionario delle proprietà |
| [setTag](#setTag-java.lang.String-) | Imposta il tag di contenuto marcato |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Costruttore per la classe operatore.

### DP {#DP-java.lang.String-}
Inizializza l'operatore.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Ottiene il dizionario delle proprietà

**Returns:**
Valore IPdfDictionary

### getTag {#getTag--}
```
public String getTag()
```

Ottiene il tag di contenuto marcato

**Returns:**
valore String

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Imposta il dizionario delle proprietà

### setTag {#setTag-java.lang.String-}
Imposta il tag di contenuto marcato

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
