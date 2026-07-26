---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per adattarsi al rettangolo specificato dalle coordinate sinistra, basso, destra e."
type: docs
weight: 1570
url: /it/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare interamente il rettangolo specificato dalle coordinate left, bottom, right e top nella finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo nella finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può provocare un comportamento imprevedibile.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Crea una destinazione esplicita remota. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Crea una destinazione esplicita remota. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e i parametri visibili. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBottom](#getBottom--) | Restituisce la coordinata verticale inferiore del rettangolo visibile. |
| [getLeft](#getLeft--) | Restituisce la coordinata orizzontale sinistra del rettangolo visibile. |
| [getRight](#getRight--) | Restituisce la coordinata orizzontale destra del rettangolo visibile. |
| [getTop](#getTop--) | Restituisce la coordinata verticale superiore del rettangolo visibile. |
| [toString](#toString--) | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Crea una destinazione esplicita remota.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Crea una destinazione esplicita remota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di destinazione del documento remoto. |
| sinistra |  | Coordinata orizzontale sinistra del rettangolo visibile. |
| inferiore |  | Coordinata verticale inferiore del rettangolo visibile. |
| destro |  | Coordinata orizzontale destra del rettangolo visibile. |
| alto |  | Coordinata verticale superiore del rettangolo visibile. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e i parametri visibili.

### getBottom {#getBottom--}
```
public double getBottom()
```

Restituisce la coordinata verticale inferiore del rettangolo visibile.

**Returns:**
valore double

### getLeft {#getLeft--}
```
public double getLeft()
```

Restituisce la coordinata orizzontale sinistra del rettangolo visibile.

**Returns:**
valore double

### getRight {#getRight--}
```
public double getRight()
```

Restituisce la coordinata orizzontale destra del rettangolo visibile.

**Returns:**
valore double

### getTop {#getTop--}
```
public double getTop()
```

Restituisce la coordinata verticale superiore del rettangolo visibile.

**Returns:**
valore double

### toString {#toString--}
```
public String toString()
```

Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitR 100 200 300 400".

**Returns:**
Valore stringa che rappresenta lo stato dell'oggetto.
