---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il posizionamento di XForm. Se l'XForm viene visualizzato sulla pagina più di una volta, tutti gli XFormPlacement associati a questo XForm avranno elementi grafici comuni, ma."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Rappresenta il posizionamento di XForm. Se XForm viene visualizzato nella pagina più di una volta, tutti gli XformPlacements associati a questo XForm avranno elementi grafici comuni, ma stati grafici diversi.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Restituisce gli elementi grafici all'interno di questo XForm. |
| [getName](#getName--) | Restituisce il nome dello XForm. |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo di delimitazione del GraphicElement. |
| [getXForm](#getXForm--) | Restituisce lo XForm associato a questo XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Ottiene o imposta la posizione nello spazio di coordinate corrente. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Restituisce gli elementi grafici all'interno di questo XForm.

**Returns:**
Istanza di GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Restituisce il nome dello XForm.

**Returns:**
valore String

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo di delimitazione del GraphicElement.

**Returns:**
Istanza Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Restituisce lo XForm associato a questo XFormPlacement.

**Returns:**
Istanza di XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Ottiene o imposta la posizione nello spazio di coordinate corrente.
