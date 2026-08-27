---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra e il contenuto della pagina ingrandito solo."
type: docs
weight: 1580
url: /it/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Rappresenta una destinazione esplicita che visualizza la pagina con la coordinata orizzontale sinistra posizionata sul bordo sinistro della finestra e i contenuti della pagina ingranditi appena a sufficienza per far rientrare l'intera altezza della pagina nella finestra. Un valore nullo per left indica che il valore corrente di quel parametro deve essere mantenuto invariato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Crea una destinazione esplicita remota. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Crea una destinazione esplicita remota. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e il parametro left. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeft](#getLeft--) | Restituisce la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra. |
| [toString](#toString--) | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Crea una destinazione esplicita remota.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Crea una destinazione esplicita remota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di destinazione del documento remoto. |
| sinistra |  | La coordinata orizzontale sinistra posizionata al bordo sinistro della finestra. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e il parametro left.

### getLeft {#getLeft--}
```
public double getLeft()
```

Restituisce la coordinata orizzontale sinistra posizionata al bordo sinistro della finestra.

**Returns:**
valore double

### toString {#toString--}
```
public String toString()
```

Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitV 100".

**Returns:**
Valore stringa che rappresenta lo stato dell'oggetto.
