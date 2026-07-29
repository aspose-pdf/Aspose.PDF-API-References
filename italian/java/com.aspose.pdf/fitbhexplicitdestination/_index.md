---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e il contenuto della pagina ingrandito appena."
type: docs
weight: 1530
url: /it/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata verticale superiore posizionata sul bordo superiore della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera larghezza del suo riquadro di delimitazione nella finestra. Un valore nullo per top indica che il valore corrente di quel parametro deve essere mantenuto invariato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Crea una destinazione esplicita remota. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Crea una destinazione esplicita remota. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Crea l'istanza e la inizializza con l'oggetto pagina DOM e il parametro top. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTop](#getTop--) | Ottiene la coordinata verticale superiore posizionata sul bordo superiore della finestra. |
| [toString](#toString--) | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Crea una destinazione esplicita remota.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Crea una destinazione esplicita remota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di destinazione del documento remoto. |
| alto |  | La coordinata verticale superiore posizionata sul bordo superiore della finestra. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Crea l'istanza e la inizializza con l'oggetto pagina DOM e il parametro top.

### getTop {#getTop--}
```
public double getTop()
```

Ottiene la coordinata verticale superiore posizionata sul bordo superiore della finestra.

**Returns:**
valore double

### toString {#toString--}
```
public String toString()
```

Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitBH 100".

**Returns:**
Valore stringa che rappresenta lo stato dell'oggetto.
