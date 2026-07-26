---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe base per l'oggetto grafico nella pagina."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Rappresenta la classe base per l'oggetto grafico nella pagina.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Rilascia tutte le risorse utilizzate dalla classe {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento è creato. Cambia quando viene chiamato SetPosition(). |
| [getOperators](#getOperators--) | Ottiene una collezione di operatori che rappresentano l'elemento. |
| [getParent](#getParent--) | Ottiene l'attuale {@link XFormPlacement} in cui si trova l'elemento. |
| [getPosition](#getPosition--) | Ottiene o imposta la posizione nello spazio di coordinate corrente. Se Parent #getParent/#setParent(XFormPlacement) non è nullo, allora l'elemento ha lo spazio di coordinate xForm. |
| [getRectangle](#getRectangle--) | Ottiene il rettangolo di delimitazione del {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Ottiene la pagina da cui viene estratto l'elemento grafico. |
| [remove](#remove--) | Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere, è meglio usare Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Converte l'elemento in una singola immagine SVG. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Converte l'elemento in una singola immagine SVG. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Ottiene o imposta la posizione nello spazio di coordinate corrente. Se Parent #getParent/#setParent(XFormPlacement) non è nullo, allora l'elemento ha lo spazio di coordinate xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Aggiunge l'elemento corrente nella pagina. Se ci sono molti elementi da aggiungere è meglio usare Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Rilascia tutte le risorse utilizzate dalla classe {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Ottiene la matrice dell'elemento grafico. La matrice viene impostata quando l'elemento è creato. Cambia quando viene chiamato SetPosition().

**Returns:**
Istanza della matrice

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Ottiene una collezione di operatori che rappresentano l'elemento.

**Returns:**
Elenco di istanze Operator

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Ottiene l'attuale {@link XFormPlacement} in cui si trova l'elemento.

**Returns:**
Istanza XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Ottiene o imposta la posizione nello spazio di coordinate corrente. Se Parent #getParent/#setParent(XFormPlacement) non è nullo, allora l'elemento ha lo spazio di coordinate xForm.

**Returns:**
Istanza di Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Ottiene il rettangolo di delimitazione del {@link GraphicElement}.

**Returns:**
Istanza Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Ottiene la pagina da cui viene estratto l'elemento grafico.

**Returns:**
Istanza della pagina

### remove {#remove--}
```
public final void remove()
```

Rimuove l'elemento corrente dalla pagina. Se ci sono molti elementi da rimuovere, è meglio usare Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Converte l'elemento in una singola immagine SVG.

**Returns:**
La stringa SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Converte l'elemento in una singola immagine SVG.

**Returns:**
La stringa SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Ottiene o imposta la posizione nello spazio di coordinate corrente. Se Parent #getParent/#setParent(XFormPlacement) non è nullo, allora l'elemento ha lo spazio di coordinate xForm.
