---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'elemento di struttura Link nella struttura logica."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

Rappresenta l'elemento di struttura Link nella struttura logica.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Regola posizione. |
| [getHyperlink](#getHyperlink--) | Ottiene o imposta il collegamento ipertestuale per l'elemento Link. |
| [getStructureTextState](#getStructureTextState--) | Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} per l'elemento corrente. Valore: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} oggetto per l'elemento corrente. |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Ottiene o imposta il collegamento ipertestuale per l'elemento Link. |
| [setText](#setText-java.lang.String-) | Aggiunge contenuto di testo all'elemento di testo corrente. |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Regola posizione.

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

Ottiene o imposta il collegamento ipertestuale per l'elemento Link.

**Returns:**
Istanza di collegamento ipertestuale

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Ottiene l'oggetto {@code /Aspose.Pdf.LogicalStructure.StructureTextState} per l'elemento corrente. Valore: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} oggetto per l'elemento corrente.

**Returns:**
Valore: oggetto StructureTextState per l'elemento di struttura del testo.

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Ottiene o imposta il collegamento ipertestuale per l'elemento Link.

### setText {#setText-java.lang.String-}
Aggiunge contenuto di testo all'elemento di testo corrente.
