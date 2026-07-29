---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe base per gli elementi di struttura del testo a livello di blocco nella struttura logica."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

Rappresenta una classe base per gli elementi di struttura del testo a livello di blocco nella struttura logica.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Regola posizione. |
| [getStructureTextState](#getStructureTextState--) | Ottiene l'oggetto {@code StructureTextState} per l'elemento corrente. Valore: oggetto {@code structureTextState} per l'elemento corrente. |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | Aggiunge contenuto di testo all'elemento di testo corrente. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Regola posizione.

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Ottiene l'oggetto {@code StructureTextState} per l'elemento corrente. Valore: oggetto {@code structureTextState} per l'elemento corrente.

**Returns:**
Valore: oggetto StructureTextState per l'elemento di struttura del testo.

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
Aggiunge contenuto di testo all'elemento di testo corrente.
