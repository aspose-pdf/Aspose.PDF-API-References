---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la destinazione esplicita che visualizza la pagina con le coordinate (sinistra, alto) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina."
type: docs
weight: 5800
url: /it/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore null per uno qualsiasi dei parametri left, top o zoom indica che il valore corrente di quel parametro deve rimanere invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore null. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Crea una destinazione esplicita remota. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Crea una destinazione esplicita remota. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e i parametri visibili. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Crea la destinazione nella posizione specificata della pagina considerando la rotazione della pagina se necessario. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Crea la destinazione alla pagina specificata. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Crea la destinazione all'angolo superiore sinistro della pagina specificata. |
| [getLeft](#getLeft--) | Ottiene la coordinata orizzontale sinistra dell'angolo superiore sinistro della finestra. |
| [getTop](#getTop--) | Ottiene la coordinata verticale superiore dell'angolo superiore sinistro della finestra. |
| [getZoom](#getZoom--) | Ottiene il fattore di zoom. |
| [toString](#toString--) | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Crea una destinazione esplicita remota.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Crea una destinazione esplicita remota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina di destinazione del documento remoto. |
| sinistra |  | Coordinata orizzontale sinistra dell'angolo superiore sinistro della finestra. |
| alto |  | Coordinata verticale superiore dell'angolo superiore sinistro della finestra. |
| zoom |  | Fattore di zoom. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Crea l'istanza e la inizializza tramite l'oggetto pagina DOM e i parametri visibili.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Crea la destinazione nella posizione specificata della pagina considerando la rotazione della pagina se necessario.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Crea la destinazione alla pagina specificata.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Crea la destinazione all'angolo superiore sinistro della pagina specificata.

### getLeft {#getLeft--}
```
public double getLeft()
```

Ottiene la coordinata orizzontale sinistra dell'angolo superiore sinistro della finestra.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Ottiene la coordinata verticale superiore dell'angolo superiore sinistro della finestra.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Ottiene il fattore di zoom.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Converte lo stato dell'oggetto in valore stringa. Esempio: "1 XYZ 100 200 3".

**Returns:**
Valore stringa che rappresenta lo stato dell'oggetto.
