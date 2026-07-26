---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'elemento di struttura LI nella struttura logica della lista."
type: docs
weight: 110
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Rappresenta l'elemento di struttura LI nella struttura logica della lista.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Aggiunge un riferimento all'{@link StructureElement} specificato all'interno di questo elemento Table of Contents Item (TOCI). Questo è tipicamente usato quando {@code ListLIElement} funge da intestazione TOC in tabelle dei contenuti nidificate. |
| [getGetElement](#getGetElement--) | Ottiene l'elemento PDF sottostante che rappresenta questa struttura TOCI. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Aggiunge un riferimento all'{@link StructureElement} specificato all'interno di questo elemento Table of Contents Item (TOCI). Questo è tipicamente usato quando {@code ListLIElement} funge da intestazione TOC in tabelle dei contenuti nidificate.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Ottiene l'elemento PDF sottostante che rappresenta questa struttura TOCI.

**Returns:**
L'Element che forma la rappresentazione strutturale di questa voce di indice.

### preSave {#preSave--}
```
public void preSave()
```
