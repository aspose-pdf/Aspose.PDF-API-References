---
title: "Elemento"
linktitle: "Elemento"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe base per gli elementi nella struttura logica."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

Rappresenta una classe base per gli elementi nella struttura logica.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Aggiunge {@code /Aspose.Pdf.LogicalStructure.Element} alla collezione di figli. |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Aggiunge {@code /Aspose.Pdf.LogicalStructure.Element} alla collezione di figli. |
| [clearChilds](#clearChilds--) | Cancella tutti i figli. |
| [findElements](#findElements-java.lang.Class-) | Trova gli Elementi di un tipo dato |
| [findElements](#findElements-java.lang.Class-boolean-) | Trova gli Elementi di un tipo dato |
| [getChildElements](#getChildElements--) | Ottiene la collezione di figli degli oggetti {@code Element}. |
| [getElementEngine](#getElementEngine--) | Ottieni l'elemento padre. |
| [getParentElement](#getParentElement--) | Ottiene la collezione padre degli oggetti {@code Element}. |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | Metodo interno |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Inserisce {@code /Aspose.Pdf.LogicalStructure.Element} nella collezione di figli all'indice specificato. |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | Inserisce {@code /Aspose.Pdf.LogicalStructure.Element} nella collezione di figli all'indice specificato. |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | Rimuove il figlio a. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | Associa un elemento di struttura all'Annotazione. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Associa un elemento di struttura all'Artifatto. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Associa un elemento di struttura all'operatore BDC del flusso di contenuto. |
| [tag](#tag-com.aspose.pdf.XForm-) | Associa un elemento di struttura al XForm del flusso di contenuto. |
| [tag](#tag-com.aspose.pdf.XImage-) | Associa un elemento di struttura allo XImage. |
| [toString](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Aggiunge {@code /Aspose.Pdf.LogicalStructure.Element} alla collezione di figli.

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Aggiunge {@code /Aspose.Pdf.LogicalStructure.Element} alla collezione di figli.

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

Cancella tutti i figli.

### findElements {#findElements-java.lang.Class-}
Trova gli Elementi di un tipo dato

### findElements {#findElements-java.lang.Class-boolean-}
Trova gli Elementi di un tipo dato

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

Ottiene la collezione di figli degli oggetti {@code Element}.

**Returns:**
Valore: collezione di figli degli oggetti {@code Element}.

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

Ottieni l'elemento padre.

**Returns:**
Valore: elemento padre.

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

Ottiene la collezione padre degli oggetti {@code Element}.

**Returns:**
Valore: collezione padre degli oggetti {@code Element}.

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

Metodo interno

**Returns:**
Elemento interno

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Inserisce {@code /Aspose.Pdf.LogicalStructure.Element} nella collezione di figli all'indice specificato.

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
Inserisce {@code /Aspose.Pdf.LogicalStructure.Element} nella collezione di figli all'indice specificato.

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

Rimuove il figlio a.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'elemento figlio. |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### tag {#tag-com.aspose.pdf.Annotation-}
Associa un elemento di struttura all'Annotazione.

### tag {#tag-com.aspose.pdf.Artifact-}
Associa un elemento di struttura all'Artifatto.

### tag {#tag-com.aspose.pdf.operators.BDC-}
Associa un elemento di struttura all'operatore BDC del flusso di contenuto.

### tag {#tag-com.aspose.pdf.XForm-}
Associa un elemento di struttura al XForm del flusso di contenuto.

### tag {#tag-com.aspose.pdf.XImage-}
Associa un elemento di struttura allo XImage.

### toString {#toString--}
```
public String toString()
```

Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
Stringa che rappresenta l'oggetto corrente.
