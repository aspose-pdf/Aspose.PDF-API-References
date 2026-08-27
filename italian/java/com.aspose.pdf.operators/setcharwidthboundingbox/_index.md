---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore d1 (imposta il glifo e il riquadro di delimitazione)."
type: docs
weight: 520
url: /it/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Classe che rappresenta l'operatore d1 (imposta il glifo e il riquadro di delimitazione).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Inizializza l'operatore SetCharWidthBoundingBox. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getLlx](#getLlx--) | Coordinata orizzontale in basso a sinistra del rettangolo di delimitazione. |
| [getLly](#getLly--) | Coordinata verticale in basso a sinistra del rettangolo di delimitazione. |
| [getUrx](#getUrx--) | Coordinata orizzontale in alto a destra del rettangolo di delimitazione. |
| [getUry](#getUry--) | Coordinata verticale in alto a destra del rettangolo di delimitazione. |
| [getWx](#getWx--) | Spostamento orizzontale del glifo. |
| [getWy](#getWy--) | Spostamento verticale del glifo. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Inizializza l'operatore SetCharWidthBoundingBox.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wx |  | Indica lo spostamento orizzontale nella coordinata del glifo. |
| wy |  | Indica lo spostamento verticale nella coordinata del glifo. Deve essere 0. |
| llx |  | Indica la coordinata X dell'angolo in basso a sinistra. |
| lly |  | Indica la coordinata Y dell'angolo in basso a sinistra. |
| urx |  | Indica la coordinata X dell'angolo in alto a destra. |
| ury |  | Indica la coordinata Y dell'angolo in alto a destra. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getLlx {#getLlx--}
```
public double getLlx()
```

Coordinata orizzontale in basso a sinistra del rettangolo di delimitazione.

**Returns:**
valore double

### getLly {#getLly--}
```
public double getLly()
```

Coordinata verticale in basso a sinistra del rettangolo di delimitazione.

**Returns:**
valore double

### getUrx {#getUrx--}
```
public double getUrx()
```

Coordinata orizzontale in alto a destra del rettangolo di delimitazione.

**Returns:**
valore double

### getUry {#getUry--}
```
public double getUry()
```

Coordinata verticale in alto a destra del rettangolo di delimitazione.

**Returns:**
valore double

### getWx {#getWx--}
```
public double getWx()
```

Spostamento orizzontale del glifo.

**Returns:**
valore double

### getWy {#getWy--}
```
public double getWy()
```

Spostamento verticale del glifo.

**Returns:**
valore double

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
Rappresentazione testuale della rappresentazione
