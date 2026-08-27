---
title: "StructureElement"
linktitle: "StructureElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe base per gli elementi di struttura nella struttura logica."
type: docs
weight: 110
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements/structureelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement

```
public abstract class StructureElement extends Element
```

Rappresenta una classe base per gli elementi di struttura nella struttura logica.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Modifica l'elemento genitore per l'elemento di struttura corrente |
| [changeParentElement](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-) | Modifica l'elemento genitore per l'elemento di struttura corrente |
| [clearId](#clearId--) | Cancella l'ID per l'elemento di struttura. |
| [generateId](#generateId--) | Genera l'ID per l'elemento di struttura. |
| [getActualText](#getActualText--) | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [getAlternativeText](#getAlternativeText--) | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [getAttributes](#getAttributes--) | Ottiene l'oggetto {@code StructureAttributeCollection}. |
| [getDefaultAttributeOwner](#getDefaultAttributeOwner--) | Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valore: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} oggetto. |
| [getExpansionText](#getExpansionText--) | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [getID](#getID--) | Ottiene l'ID per l'elemento di struttura. Valore: ID dell'elemento di struttura. |
| [getLanguage](#getLanguage--) | Ottiene o imposta la lingua per l'elemento di struttura. |
| [getPage](#getPage--) | Ottiene la pagina su cui alcuni o tutti gli elementi figlio verranno renderizzati. |
| [getS](#getS--) |  |
| [getStructureType](#getStructureType--) | Ottiene il tipo dell'elemento di struttura. |
| [getTitle](#getTitle--) | Ottiene o imposta il titolo per l'elemento di struttura. |
| [remove](#remove--) | Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio, l'oggetto corrispondente dal documento. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent--) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio e l'oggetto corrispondente dal documento. Inserisce gli oggetti figlio dell'oggetto rimosso nella precedente collezione di oggetti figlio del padre a partire dall'indice dell'oggetto rimosso. |
| [removeAndMoveItsChildObjectsToItsParent](#removeAndMoveItsChildObjectsToItsParent-boolean-) | Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio e l'oggetto corrispondente dal documento. Inserisce gli oggetti figlio dell'oggetto rimosso nella precedente collezione di oggetti figlio del padre a partire dall'indice dell'oggetto rimosso. |
| [setActualText](#setActualText-java.lang.String-) | Ottiene o imposta il testo effettivo per l'elemento di struttura. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Ottiene o imposta il testo alternativo per l'elemento di struttura. |
| [setExpansionText](#setExpansionText-java.lang.String-) | Ottiene o imposta il testo di espansione per l'elemento di struttura. |
| [setId](#setId-java.lang.String-) | Imposta l'ID per l'elemento di struttura. |
| [setLanguage](#setLanguage-java.lang.String-) | Ottiene o imposta la lingua per l'elemento di struttura. |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | imposta Elemento Padre |
| [setTag](#setTag-java.lang.String-) | Imposta il tag personalizzato per l'elemento di struttura. |
| [setTitle](#setTitle-java.lang.String-) | Ottiene o imposta il titolo per l'elemento di struttura. |
| [tag](#tag-com.aspose.pdf.Annotation-) | Associa un elemento di struttura all'Annotazione. |
| [tag](#tag-com.aspose.pdf.Artifact-) | Associa un elemento di struttura all'Artifatto. |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | Associa un elemento di struttura all'operatore BDC del flusso di contenuto. |
| [tag](#tag-com.aspose.pdf.XForm-) | Associa un elemento di struttura al XForm del flusso di contenuto. |
| [tag](#tag-com.aspose.pdf.XImage-) | Associa un elemento di struttura allo XImage. |
| [toString](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Modifica l'elemento genitore per l'elemento di struttura corrente

### changeParentElement {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-boolean-}
Modifica l'elemento genitore per l'elemento di struttura corrente

### clearId {#clearId--}
```
public final void clearId()
```

Cancella l'ID per l'elemento di struttura.

### generateId {#generateId--}
```
public final void generateId()
```

Genera l'ID per l'elemento di struttura.

### getActualText {#getActualText--}
```
public final String getActualText()
```

Ottiene o imposta il testo effettivo per l'elemento di struttura.

**Returns:**
Valore: Testo effettivo dell'elemento di struttura.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Ottiene o imposta il testo alternativo per l'elemento di struttura.

**Returns:**
Valore: Testo alternativo dell'elemento di struttura.

### getAttributes {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```

Ottiene l'oggetto {@code StructureAttributeCollection}.

**Returns:**
{@code StructureAttributeCollection} oggetto.

### getDefaultAttributeOwner {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```

Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard}. Valore: {@code /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard} oggetto.

**Returns:**
Istanza di AttributeOwnerStandard

### getExpansionText {#getExpansionText--}
```
public final String getExpansionText()
```

Ottiene o imposta il testo di espansione per l'elemento di struttura.

**Returns:**
Valore: Testo di espansione dell'elemento di struttura.

### getID {#getID--}
```
public final String getID()
```

Ottiene l'ID per l'elemento di struttura. Valore: ID dell'elemento di struttura.

**Returns:**
valore String

### getLanguage {#getLanguage--}
```
public final String getLanguage()
```

Ottiene o imposta la lingua per l'elemento di struttura.

**Returns:**
Valore: Lingua dell'elemento di struttura.

### getPage {#getPage--}
```
public final Page getPage()
```

Ottiene la pagina su cui alcuni o tutti gli elementi figlio verranno renderizzati.

**Returns:**
Istanza della pagina

### getS {#getS--}
```
public final com.aspose.pdf.engine.data.IPdfName getS()
```



### getStructureType {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```

Ottiene il tipo dell'elemento di struttura.

**Returns:**
Valore: {@code StructureTypeStandard} oggetto dell'elemento di struttura.

### getTitle {#getTitle--}
```
public final String getTitle()
```

Ottiene o imposta il titolo per l'elemento di struttura.

**Returns:**
Valore: Titolo dell'elemento di struttura.

### remove {#remove--}
```
public final void remove()
```

Rimuove: un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio, l'oggetto corrispondente dal documento.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent--}
```
public final void removeAndMoveItsChildObjectsToItsParent()
```

Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio e l'oggetto corrispondente dal documento. Inserisce gli oggetti figlio dell'oggetto rimosso nella precedente collezione di oggetti figlio del padre a partire dall'indice dell'oggetto rimosso.

### removeAndMoveItsChildObjectsToItsParent {#removeAndMoveItsChildObjectsToItsParent-boolean-}
```
public final void removeAndMoveItsChildObjectsToItsParent(boolean checkIfChildObjectsCanBeMovedToParent)
```

Rimuove un elemento dalla struttura, un riferimento ad esso dall'oggetto padre, riferimenti ad esso dagli oggetti figlio e l'oggetto corrispondente dal documento. Inserisce gli oggetti figlio dell'oggetto rimosso nella precedente collezione di oggetti figlio del padre a partire dall'indice dell'oggetto rimosso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| checkIfChildObjectsCanBeMovedToParent |  | Verifica se gli oggetti figlio dell'oggetto rimosso possono essere inseriti nella collezione di oggetti figlio del suo padre. |

### setActualText {#setActualText-java.lang.String-}
Ottiene o imposta il testo effettivo per l'elemento di struttura.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Ottiene o imposta il testo alternativo per l'elemento di struttura.

### setExpansionText {#setExpansionText-java.lang.String-}
Ottiene o imposta il testo di espansione per l'elemento di struttura.

### setId {#setId-java.lang.String-}
Imposta l'ID per l'elemento di struttura.

### setLanguage {#setLanguage-java.lang.String-}
Ottiene o imposta la lingua per l'elemento di struttura.

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
imposta Elemento Padre

### setTag {#setTag-java.lang.String-}
Imposta il tag personalizzato per l'elemento di struttura.

### setTitle {#setTitle-java.lang.String-}
Ottiene o imposta il titolo per l'elemento di struttura.

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
