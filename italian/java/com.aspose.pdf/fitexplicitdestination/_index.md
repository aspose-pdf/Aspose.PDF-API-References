---
title: "FitExplicitDestination"
linktitle: "FitExplicitDestination"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per adattare l'intera pagina all'interno della finestra sia orizzontalmente che verticalmente. Se il."
type: docs
weight: 1550
url: /it/java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare l'intera pagina nella finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando la pagina nella finestra nell'altra dimensione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Crea una destinazione esplicita remota. |
| [FitExplicitDestination](#FitExplicitDestination-int-) | Crea una destinazione esplicita remota. |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | Crea una destinazione esplicita locale. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [toString](#toString--) | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 Fit". |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
Crea una destinazione esplicita remota.

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

Crea una destinazione esplicita remota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di destinazione del documento remoto. |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
Crea una destinazione esplicita locale.

### toString {#toString--}
```
public String toString()
```

Converte lo stato dell'oggetto in valore stringa. Esempio: "1 Fit".

**Returns:**
Valore stringa che rappresenta lo stato dell'oggetto.
